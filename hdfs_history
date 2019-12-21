  684  su beski
  685  hadoop fs -ls
  686  pwd
  687  cd /usr/local/hadoop_store/hdfs/datanode/current/BP-293498989-127.0.0.1-1563204412417/current/finalized/subdir0/subdir0/
  688  ls -lart
  689  pwd
  690  hadoop fs -cat hadoop/sample.txt
  691  pwd
  692  rm test.txt
  693  cd /tmp
  694  rm test.txt
  695  hadoop fs -copyToLocal /user/hduser/test.txt /tmp
  696  hadoop fs -copyToLocal /user/hduser/test.txt /tmp/inceptez.txt
  697  cat /tmp/inceptez.txt
  698  cat /tmp/test.txt
  699  pwd
  700  hadoop fs -ls hadoop/*.txt
  701  hadoop fs -put test.txt hadoop/
  702  hadoop fs -cat hadoop/*.txt
  703  hadoop fs -rm hadoop/*.txt
  704  hadoop fs -cp /user/hduser/test.txt /user/hduser/test2.txt
  705  hadoop fs -cp /user/hduser/test.txt /user/hduser/test33.txt
  706  hadoop fs -mv /user/hduser/test.txt /user/hduser/test333.txt
  707  ifconfig
  708  hadoop fs -stat
  709  hdfs fsck / -corruptedBlockFiles
  710  hdfs fsck / -listCorruptedFileBlocks
  711  hdfs fsck / -list-corruptedfileblocks
  712  hdfs fsck / -list-corruptfileblocks
  713  hdfs fsck / -list-corruptfileblocks | awk -F" " '{ print $2 }'
  714  hdfs fsck / -blocks -files
  715  hadoop fs -get test2.txt /home/hduser/test3.txt
  716  hadoop fs -get -f test2.txt /home/hduser/test3.txt
  717  rm ~/test3.txt
  718  hadoop fs -get -f test2.txt /home/hduser/test3.txt
  719  hadoop fs -get test2.txt /home/hduser/test3.txt
  720  pwd
  721  hadoop fs -put -f /home/hduser/filename 
  722  hadoop fs -tail filename
  723  hadoop fs -head filename
  724  hadoop fs -tail filename | tail -1
  725  hadoop fs -cat filename | head -2 > headfilename
  726  cat headfilename
  727* 
  728* 
  729  hadoop fs -touchz hadoop/test4.txt
  730  dt=`date`
  731  hadoop fs -touchz hadoop/test$dt.txt
  732* hadoop fs -touchz "/user/hduser/hadoop/test.txt"
  733  echo $dt
  734  hadoop fs -ls hadoop/test4.txt
  735  hadoop fs -chmod 600 hadoop/test4.txt
  736  hadoop fs -moveFromLocal ~/test.txt /user/hduser/test.txt
  737  cd ~
  738  ls test.txt
  739  echo somedata > test1.txt
  740  hadoop fs -cat hadoop/test.txt
  741  hadoop fs -cat hadoop/test4.txt
  742  hadoop fs -appendToFile test1.txt hadoop/test4.txt
  743  echo additionaldata > test1.txt
  744  hadoop fs -cat hadoop/test4.txt
  745  hadoop fs -appendToFile test1.txt hadoop/test4.txt
  746  hadoop fs -cat hadoop/test4.txt
  747  locate hadoop-defaults.xml
  748  locate defaults.xml
  749  cd /usr/local/hadoop/etc/hadoop
  750  cd ../../
  751  locate default
  752  locate defaults.xml
  753  locate defaults.conf
  754  pwd
  755  ls -lart
  756  cd share/
  757  ls -lart
  758  cd hadoop/
  759  ls -lart
  760  cd hdfs/
  761  ls -lart
  762  ls *defaul*
  763  pwd
  764  cd ..
  765  ls -lart
  766  cd ..
  767  pwd
  768  ls -lart
  769  locate default
  770  vi /usr/local/hadoop/share/doc/hadoop/hadoop-project-dist/hadoop-hdfs/hdfs-default.xml
  771  cd ~
  772  tail -10 filename
  773  tail -10 filename > filename10
  774  cat filename10 | hadoop fs -put
  775  hadoop fs -head filename
  776  hadoop fs -cat filename | head -2
  777  tail -5 filename 
  778  hadoop fs -cat filename | grep -v line5
  779  hadoop fs -cat filename | grep -v line5 > filenwithoutline5
  780  hadoop fs -vi filename
  781  hadoop fs -cat filename  > filenwithoutline5
  782  hadoop fs -cat filename | sed -e '-n5'
  783  hadoop fs -cat filename | sed -e '5d'
  784* 
  785  hadoop fs -cat filename
  786  hadoop fs -du -s -h hadoop
  787  hadoop fsck - /
  788  hadoop fsck - / | grep CORRUPT
  789  hadoop fsck - / -files -blocks
  790  hadoop fsck - / -delete
  791  hadoop fsck - /
  792  hadoop balancer
  793  hadoop fs -cat 2~test2.txt
  794  hadoop fs -cat test2.txt
  795  hadoop fs -stat %r test2.txt
  796  hadoop fs -ls test2.txt
  797* hadoop fs -setrep -w 20 test2.txt
  798  hadoop fs -stat %r test2.txt
  799  hadoop fs -setrep -w 1 test2.txt
  800  hadoop fs -setrep -w 2 test2.txt
  801  hadoop fs -stat %r test2.txt
  802  hadoop fs -setrep -w 1 test2.txt
  803  hadoop fs -ls test2.txt
  804  hadoop fs -chown inceptez:inceptez test2.txt
  805  hadoop fs -ls test2.txt
  806  hadoop fs -chgrp hadoop test2.txt
  807  hadoop fs -ls test2.txt
  808  hdfs dfsadmin -safemode get
  809  hadoop fs -setrep -w 3 test2.txt
  810  hadoop fsck
  811  hadoop fsck / -blocks
  812  hadoop fsck / -blocks | under
  813  hadoop fsck / -blocks | grep under
  814  hadoop fsck / -blocks | grep "Under Replica"
  815  hadoop fsck / -blocks | grep "Under replica"
  816  hadoop fsck / -blocks -files | grep "Under replica"
  817  hadoop fsck hadoop/filename -blocks
  818  hadoop fsck filename -blocks
  819* hadoop fsck filename -blocks -files
