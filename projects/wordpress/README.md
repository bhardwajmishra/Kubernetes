First you need to create secret.
Command: kubectl create secret generic wp-config --from-file=wp-config.php -n wp

Then you need to apply deployment file.

