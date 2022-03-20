# rewind-
&lt;?php $file = fopen("test.txt","r");  //Change position of file pointer fseek($file,"15");  //Set file pointer to 0 rewind($file);  fclose($file); ?>
