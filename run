def main_menu
  puts "⡏⠉⠛⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣿"
  puts "⣿⠀⠀⠀⠈⠛⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠛⠉⠁⠀⣿"
  puts "⣿⣧⡀⠀⠀⠀⠀⠙⠿⠿⠿⠻⠿⠿⠟⠿⠛⠉⠀⠀⠀⠀⠀⣸⣿"
  puts "⣿⣿⣷⣄⠀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣴⣿⣿⣿"
  puts "⣿⣿⣿⣿⠏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠠⣴⣿⣿⣿⣿⣿"
  puts "⣿⣿⣿⡟⠀⠀⢰⣹⡆⠀⠀⠀⠀⠀⠀⣭⣷⠀⠀⠀⠸⣿⣿⣿⣿"
  puts "⣿⣿⣿⠃⠀⠀⠈⠉⠀⠀⠤⠄⠀⠀⠀⠉⠁⠀⠀⠀⠀⢿⣿⣿⣿"
  puts "⣿⣿⣿⢾⣿⣷⠀⠀⠀⠀⡠⠤⢄⠀⠀⠀⠠⣿⣿⣷⠀⢸⣿⣿⣿"
  puts "⣿⣿⣿⡀⠉⠀⠀⠀⠀⠀⢄⠀⢀⠀⠀⠀⠀⠉⠉⠁⠀⠀⣿⣿⣿"
  puts "⣿⣿⣿⣧⠀⠀⠀⠀⠀⠀⠀⠈⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢹⣿⣿"
  puts "⣿⣿⣿⣿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿"
  puts "      R‌e‌z‌a‌ J‌o‌k‌e‌r‌ "
  puts "\nChoose a section:"
  puts "1. Information Gathering"
  puts "2. Vulnerability Analysis"
  puts "3. Web Hacking"
  puts "4. Database Assessment"
  puts "5. Exit"
  
  print "\033[31mWhich option? \033[0m"  # Prompt in red
  option = gets.chomp.to_i
  case option
  when 1
    information_gathering
  when 2
    vulnerability_analysis
  when 3
    web_hacking
  when 4
    database_assessment
  when 5
    exit
  else
    puts "Invalid option. Try again."
    main_menu
  end
end

def information_gathering
  puts "\nInformation Gathering Menu:"
  puts "1. Download zphisher"
  puts "2. Download Red Hawk"
  puts "3. Download Xshell"
  puts "4. Back to Main Menu"

  print "\033[31mWhich option? \033[0m"
  option = gets.chomp.to_i
  case option
  when 1
    system('git clone https://github.com/zphisher/zphisher.git')
  when 2
    system('git clone https://github.com/Tuhinshubhra/Red_Hawk.git')
  when 3
    system('git clone https://github.com/hsapp/XShell.git')
  when 4
    main_menu
  else
    puts "Invalid option. Try again."
    information_gathering
  end
end

def vulnerability_analysis
  puts "\nVulnerability Analysis Menu:"
  puts "1. Download SH33LL"
  puts "2. Download XAttacker"
  puts "3. Download SQLiv"
  puts "4. Download Sn1per"
  puts "5. Back to Main Menu"

  print "\033[31mWhich option? \033[0m"
  option = gets.chomp.to_i
  case option
  when 1
    system('git clone https://github.com/EmpireProject/SH33LL.git')
  when 2
    system('git clone https://github.com/Moham3dRizky/XAttacker.git')
  when 3
    system('git clone https://github.com/CyberGus/SQliven.git')
  when 4
    system('git clone https://github.com/1N3/Sn1per.git')
  when 5
    main_menu
  else
    puts "Invalid option. Try again."
    vulnerability_analysis
  end
end

def web_hacking
  puts "\nWeb Hacking Menu:"
  puts "1. Download wpscan"
  puts "2. Download bug report"
  puts "3. Download SH33LL"
  puts "4. Download Websploit"
  puts "5. Back to Main Menu"

  print "\033[31mWhich option? \033[0m"
  option = gets.chomp.to_i
  case option
  when 1
    system('git clone https://github.com/wpscanteam/wpscan.git )
  when 2
    system('git clone https://github.com/marioyhzkiell/bugreport.git')
  when 3
    system('git clone https://github.com/EmpireProject/SH33LL.git')
  when 4
    system('git clone https://github.com/websploit/websploit.git')
  when 5
    main_menu
  else
    puts "Invalid option. Try again."
    web_hacking
  end
end

def database_assessment
  puts "\nDatabase Assessment Menu:"
  puts "1. Download DbDat"
  puts "2. Download sqlmap"
  puts "3. Download NoSQLMap"
  puts "4. Back to Main Menu"

  print "\033[31mWhich option? \033[0m"
  option = gets.chomp.to_i
  case option
  when 1
    system('git clone https://github.com/PrayagSukhwal/DbDat.git')
  when 2
    system('git clone https://github.com/sqlmapproject/sqlmap.git')
  when 3
    system('git clone https://github.com/cs50/NoSQLMap.git')
  when 4
    main_menu
  else
    puts "Invalid option. Try again."
    database_assessment
  end
end

main_menu
