color1 = '\033[38;5;53m'
color2 = '\033[38;5;54m'
color3 = '\033[38;5;55m'
color4 = '\033[38;5;56m'
color5 = '\033[38;5;57m'

color6 = '\033[38;5;17m'
color7 = '\033[38;5;18m'
color8 = '\033[38;5;19m'
color9 = '\033[38;5;20m'
color10 = '\033[38;5;21m'

color11 = '\033[38;5;25m'
color12 = '\033[38;5;26m'
color13 = '\033[38;5;27m'

color14 = '\033[38;5;31m'
color15 = '\033[38;5;32m'
color16 = '\033[38;5;33m'



# LISTA DE CORES
dic_color = [
    color1, color1, color2, color2, color3, color3, color4, color4, color5, color5, color6, color7, color8, color9, color10, color11, color12, color13, color14,
    color15, color16, color16]


txt = (r'''                                                                                             
`7MMM.     ,MMF'`7MMF'`7MM"""Yb.   `7MN.   `7MF'`7MMF'  .g8"""bgd  `7MMF'  `7MMF'MMP""MM""YMM 
  MMMb    dPMM    MM    MM    `Yb.   MMN.    M    MM  .dP'     `M    MM      MM  P'   MM   `7 
  M YM   ,M MM    MM    MM     `Mb   M YMb   M    MM  dM'       `    MM      MM       MM      
  M  Mb  M' MM    MM    MM      MM   M  `MN. M    MM  MM             MMmmmmmmMM       MM      
  M  YM.P'  MM    MM    MM     ,MP   M   `MM.M    MM  MM.    `7MMF'  MM      MM       MM      
  M  `YM'   MM    MM    MM    ,dP'   M     YMM    MM  `Mb.     MM    MM      MM       MM      
.JML. `'  .JMML..JMML..JMMmmmdP'   .JML.    YM  .JMML.  `"bmmmdPY  .JMML.  .JMML.   .JMML.                                                                                     
''').strip()

from math import ceil

print('\n')
split = txt.split(None, 16)      # Tudo
split_line = txt.split('\n')
num_lines = len(split_line)      # Numero de \n

process_number = 0
count = -1

for c in range(num_lines):
    print('')
    # PEGAR A 1 LINHA
    line1 = split_line[process_number]            # Linha 1

    # DIVIDIR 1 LINHA POR 12
    num_line1 = len(line1)           # Num de caracteres da 1 linha
    num_line1_12 = ceil(num_line1 / 16)   # Num de caracteres da 1 linha / 12

    # CRIAR LISTA COM A 1 LINHA CORTADA DE 12 EM 12
    replace_order = 1
    replace_order_1 = 0

    plus_fim = num_line1_12
    plus_inicio = 0
    list12 = []
    for c in range(16):
        list12.append(line1[plus_inicio:plus_fim])
        plus_fim += num_line1_12
        plus_inicio += num_line1_12

    # DEGRADE DA 1 LINHA
    list12_count = 0
    color = 'mid.vrc'
    count += 1
    for c in range(16):
        color = dic_color[count]
        count += 1
        # print('\n{:{}}'.format(f'{color}■'*div_line, num_line), end='')
        print(f'{color}{list12[list12_count]}', end='')
        list12_count += 1
    process_number += 1
    count -= 16
# FAZER TODO O PROCESSO PARA AS OUTRAS LINHAS
