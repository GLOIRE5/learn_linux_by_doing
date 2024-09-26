1. Gloire deleted the file "test-1" in the data directory using this command rm test-1
2. Tedla moved the file "top-5-lowest-temparatures.csv" to the analyzed directory using mv top-5-lowest-temparatures.csv analyzed 
3. Ibra Gold ensured that each file follows the required naming convention which is “top-5...” using the mv command.
4. Beni removed any duplicated values from the files using "find ~/learn_linux_by_doing -type f -name "*.csv" -exec sh -c 'sort "$0" | uniq > "$0.new" && mv "$0.new" "$0"' {} \;"
5. Ariik sorted the top 5 highest temparatures using the command "sort -t, -k3,3nr satelite_temperature_data.csv | head -n 5 > ../analyzed/top-5-highest-temparatures.csv"
6. Divine created a new branch called divine using "git branch && git checkout" and sorted the top 5 lowest temparatures using the command "sort -t, -k3,3n satelite_temperature_data.csv | head -n 5 > ../analyzed/top-5-lowest-temparatures.csv"
7. Gloire merged the main branch with divine branch using command "git merge divine"
8. Beni extracted the heat record of Rwanda and saved it to country-heat_data.csv using the command "grep "^Rwanda," satelite_temperature_data.csv > ../analyzed/country-heat_data.csv"

