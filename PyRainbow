light_red = '\033[1;91m'
red = '\033[1;31m'

light_yellow = '\033[1;93m'
yellow = '\033[1;33m'

light_green = '\033[1;92m'
green = '\033[1;32m'

light_blue = '\033[1;94m'
blue = '\033[1;34m'

light_cyan = '\033[1;96m'
cyan = '\033[1;36m'

light_magenta = '\033[1;95m'
magenta = '\033[1;35m'

white = '\033[1;97m'

light_gray = '\033[1;37m'
dark_gray = '\033[1;90m'

black = '\033[1;30m'

negrito = '\033[;1m'
inverte = '\033[;7'
clear = '\033[0;0m'

print(f'''
{light_red}■ {red}■ {light_yellow}■ {yellow}■ 
{green}■ {light_green}■ {light_blue}■ {blue}■ 
{cyan}■ {light_cyan}■ {light_magenta}■ {magenta}■
{white}■ {light_gray}■ {dark_gray}■ {black}■{clear}''')


"""txt = ('''
■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■
■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■
■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■
■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■
■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■'
''')"""

# LISTA DE CORES
dic_color = [
    light_red, red, light_yellow, yellow, green, light_green, light_blue, blue, cyan, light_cyan, light_magenta,
    magenta]


txt = (r'''
`7MMM.     ,MMF'`7MMF'`7MM"""Yb.   `7MN.   `7MF'`7MMF'  .g8"""bgd  `7MMF'  `7MMF'MMP""MM""YMM 
  MMMb    dPMM    MM    MM    `Yb.   MMN.    M    MM  .dP'     `M    MM      MM  P'   MM   `7 
  M YM   ,M MM    MM    MM     `Mb   M YMb   M    MM  dM'       `    MM      MM       MM      
  M  Mb  M' MM    MM    MM      MM   M  `MN. M    MM  MM             MMmmmmmmMM       MM      
  M  YM.P'  MM    MM    MM     ,MP   M   `MM.M    MM  MM.    `7MMF'  MM      MM       MM      
  M  `YM'   MM    MM    MM    ,dP'   M     YMM    MM  `Mb.     MM    MM      MM       MM      
.JML. `'  .JMML..JMML..JMMmmmdP'   .JML.    YM  .JMML.  `"bmmmdPY  .JMML.  .JMML.   .JMML.                                                |__/                                    
''').strip()

print('\n')
split = txt.split(None, 12)      # Tudo
split_line = txt.split('\n')
num_lines = len(split_line)      # Numero de \n

process_number = 0
from math import ceil

for c in range(num_lines):
    print('')
    # PEGAR A 1 LINHA
    line1 = split_line[process_number]            # Linha 1

    # DIVIDIR TUDO POR 12
    num_all = len(txt)               # Num de caracteres (incluindo espaço)
    num_all_12 = num_all // 12       # Num de caracteres / 12

    # DIVIDIR 1 LINHA POR 12
    num_line1 = len(line1)           # Num de caracteres da 1 linha
    num_line1_12 = ceil(num_line1 / 12)   # Num de caracteres da 1 linha / 12

    # CRIAR LISTA COM A 1 LINHA CORTADA DE 12 EM 12
    replace_order = 1
    replace_order_1 = 0

    plus_fim = num_line1_12
    plus_inicio = 0
    list12 = []
    for c in range(12):
        list12.append(line1[plus_inicio:plus_fim])
        plus_fim += num_line1_12
        plus_inicio += num_line1_12

    # DEGRADE DA 1 LINHA
    list12_count = 0
    count = 0
    color = 'mid.vrc'
    for c in range(12):
        color = dic_color[count]
        count += 1
        # print('\n{:{}}'.format(f'{color}■'*div_line, num_line), end='')
        print(f'{color}{list12[list12_count]}', end='')
        list12_count += 1
    process_number += 1

# FAZER TODO O PROCESSO PARA AS OUTRAS LINHAS






# CRIAR LISTA COM TEXTO CORTADO DE 12 EM 12
'''count_12 = 0
count_line = 0
for c in range(len(line1)):
    count_line += 1
    count_12 += 1
    if count_12 == 12:
        line_12 = (line1[:count_line])
    if count_12 == 24:
        line_24 = (line1[line_12:count_line])'''

# CRIAR LISTA COM TEXTO CORTADO DE 12 EM 12
'''replace_order = 1
replace_order_1 = 0

plus = 12
list = []
for c in range(num_line):
    list.append(line[0:plus])
    plus += 12

for c in range(len(list)):
    list[replace_order].replace(list[replace_order_1], '')
    replace_order += 1
    replace_order_1 += 1
print(list)'''
