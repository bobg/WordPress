# Deploying a new version of Wordpress

1. `cd /var/www`
2. `rm -r geebobg.old geebobg.new`
3. `cp -a geebobg geebobg.new`
4. `cp -a ...newwordpress/* geebobg.new`
5. `mv geebobg geebobg.old && mv geebobg.new geebobg`
