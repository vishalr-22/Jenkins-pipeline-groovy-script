node {
      for (i=0; i<2; i++) { 
           stage "Stage #"+i
           print 'This is the stage #' +i
           if (i==0)
           {
               echo 'Running on Stage #0'
           }
           else {
               build 'Tutorial-pipeline'
               echo 'Running on Stage #1'
           }
      }
}
