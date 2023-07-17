                           llcccccclll 
                         lolllccc clllllc 
                        oolloodkO0kdoooll 
                      cll ood0NNNXOol  olc  
                     cllc lookKNNX0kxl  lllc  
                  ooclll  lkxkKNX0kkko  lolllc  
                  lllloo  o0KXNNK0KXKd  loooollc  
                 ccclllo  lOXXXXKKXNKo  loooolllc 
                ccccllcl   lOXXXXXX0d  cllooolllc 
               ccllllccc    dO0000Oo    llooooooc 
               cllolllc,.  .cxkkkkxl     ccloooc 
               cllllloc,.   .,.ol.'..   ., ccllllc  
               cccl...,..  .............,,'',lllc 
              ,..''..''.......................'lcl 
             ,................................., 
             ..................................' 
            '...................................,
            ....................................' 
           '.....................................,
          ,......................................' 
          '.......................................


     llcccccclll 
    lolllccc clllllc 
   oolloodkO0kdoooll 
   cll ood0NNNXOol  olc  
   cllc lookKNNX0kxl  lllc  
   ooclll  lkxkKNX0kkko  lolllc  
    llllooo  O0KXNNK0KXKd  loooollc  
   ccclllo  lOXXXXKKXNKo  loooolllc 
   ccccllcl   lOXXXXXX0d  cllooolllc 
  ccllllccc    dO0000Oo    llooooooc 
  cllolllc,.  .cxkkkkxl     ccloooc 
  cllllloc,.   .,.ol.'..   ., ccllllc  
  cccl...,..  .............,,'',lllc 
,..''..''.......................'lcl 
,................................., 
..................................' 
'...................................,
....................................' 
'.....................................,
,......................................' 
'.......................................

              switch (args[1]) {
                case "Home":
              console.log(args[1])
              content.innerHTML += '<p class="commandresult">No such file or directory in this folder, Did you mean "/Home/guest"</p><br>';
              break;
                case "Pictures":
              console.log(args[1])
              if (directory == "Home") {
              directory = "Pictures"
              content.innerHTML += '<p class="commandresult">You are now in /Home/guest/Pictures</p><br>';
              }
              else {
              content.innerHTML += '<p class="commandresult">No such file or directory in this folder, Did you mean "/Home/guest/Pictures"</p><br>';
              }
              break;
                case "Desktop":
              console.log(args[1])
              if (directory == "Home") {
              directory = "Desktop"
              content.innerHTML += '<p class="commandresult">You are now in /Home/guest/Desktop</p><br>';
              }
              else {
              content.innerHTML += '<p class="commandresult">No such file or directory in this folder, Did you mean "/Home/guest/Desktop"</p><br>';
              }
              break;
                case "Documents":
              console.log(args[1])
              if (directory == "Home") {
              directory = "Documents"
              content.innerHTML += '<p class="commandresult">You are now in /Home/guest/Documents</p><br>';
              }
              else{
              content.innerHTML += '<p class="commandresult">No such file or directory in this folder, Did you mean "/Home/guest/Documents"</p><br>';
              }
              break;
                case "Videos":
              console.log(args[1])
              if (directory == "Home") {
              directory = "Videos"
              content.innerHTML += '<p class="commandresult">You are now in /Home/guest/Videos</p><br>';
              }
              else{
              content.innerHTML += '<p class="commandresult">No such file or directory in this folder, Did you mean "/Home/guest/Videos"</p><br>';
              }
              break;
                case "Homework":
              console.log(args[1])
              if (directory == "Desktop") {
              directory = "Homework"
              content.innerHTML += '<p class="commandresult">You are now in /Home/guest/Desktop/Homework</p><br>';
              }
              else{
              content.innerHTML += '<p class="commandresult">No such file or directory in this folder, Did you mean "/Home/guest/Desktop/Homework"</p><br>';
              }
              break;
                case "/Home/guest":
              console.log(args[1])
              directory = "Home"
              content.innerHTML += '<p class="commandresult">You are now in /Home/guest</p><br>';
              break;
                case "/Home/guest/Pictures":
              console.log(args[1])
              directory = "Pictures"
              content.innerHTML += '<p class="commandresult">You are now in /Home/guest/Pictures</p><br>';
              break;
                case "/Home/guest/Desktop":
              console.log(args[1])
              directory = "Desktop"
              content.innerHTML += '<p class="commandresult">You are now in /Home/guest/Desktop</p><br>';
              break;
                case "/Home/guest/Documents":
              console.log(args[1])
              directory = "Documents"
              content.innerHTML += '<p class="commandresult">You are now in /Home/guest/Documents</p><br>';
              break;
                case "/Home/guest/Videos":
              console.log(args[1])
              directory = "Videos"
              content.innerHTML += '<p class="commandresult">You are now in /Home/guest/Videos</p><br>';
              break;
                case "/Home/guest/Desktop/Homework":
              console.log(args[1])
              directory = "Homework"
              content.innerHTML += '<p class="commandresult">You are now in /Home/guest/Desktop/Homework</p><br>';
              break;

              default:
              if (content === null) {
                      return}
                  content.innerHTML += `<p class="commandresult">No such file or directory called ${args[1]} in this folder, type ls for a list of folders, or use "cd /Home/guest" to go back to Home.</p><br>`;
                  break;
              }
              ▒▒▒▒▒▓▒▒▒▓▒▒▒▒▒▒▒▒▒▒▒▒▒                                    
              ▒▓▒▒▒▒▒▒▒▒▒▓▓▓▓▓▓▓▒▒▒▒▒▒▒▒▓▒                                 
           ▒▒▓▒▒▒▒▒▒▒▒▓▓▓▓▓▓▓▓▓▓▓▒▒▒▒▒▒▒▒▒▒                                
         ▒▒▒▒▒▒▒▒▒▒▒▒▓▒▒▒▒▓▓▓▓▓▓▒▒▒▒▒▒▒▒▒▒▒▓▒                              
        ▓▒▒▒▓▒▒▒▒▒▒▒▓▒▒▒▒▓▓▒▒▒▓▓▓▓▒▒▒▒▒▒▒▒▒▒▒▓▒                            
        ▓▒▓▓▒▒▒▒▒▒▓▓▒▒▒▒▓▒     ▒▒▒▓▒▒▒▒▒▒▒▒▒▒▒▓▒                           
        ▓▓▓▒▒▒▒▓▓▒▒▒▒▒▒▓▒      ▒▒▒▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒                          
        ▓▓▒▒▒▒▓▓▒▒▒▒▒▒▓▒        ▒▒▒▓▒▒▒▒▒▒▒▒▒▒▒▒▓                          
       ▓▒▓▒▒▒▓▓▒▒▒▒▒▓▓▒▒         ▒▒▓▓▓▒▒▒▒▒▒▒▒▒▒▓▒                         
      ▓▒▓▓▒▒▒▓▓▓▒▓▓▓▒▒  ▒      ▒▒▒▒▒▒▓▓▒▒▒▒▒▒▒▒▒▒▓▒                        
    ▒▓▒▓▓▒▒▒▓▓▓▓▓▒▒▒▒▓▒▒▒   ▒▒▒▓▒▓▒▒▒▓▓▓▒▒▒▒▒▒▒▒▒▒▒▓▒▒                     
 ▒▒▓▓▓▓▓▒▒▒▒▓▓▓▓▓▒▒▒ ▒▒▒    ▒▒ ▒▒▒ ▒▒▓▓▓▓▒▒▒▒▒▒▒▒▒▒▒▒▓▒                    
▒▓▒▒▒▓▓▒▒▒▒▒▒▒▓▓▓▓▓▒▒▒▒▒▒▒    ▒▒ ▒▒▒▒ ▒▓▓▓▓▓▒▒▒▒▒▒▒▒▒▒▒▒▒▓                   
▓▒▒▒▒▓▓▒▒▒▒▒▒▒▓▓▓▓▓▒▒         ▒▒      ▒▓▓▓▓▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▓▒▒▓▒              
▒▓▒▒▓▓▓▒▒▓▒▒▒▒▒▒▓▓▓▒▒          ▒      ▒▓▓▓▓▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▓              
▒▒▓▒▒▓▓▒▒▓▓▒▓▓▒▒▒▒▒▓▓▒▒      ▒▒ ▒       ▒▓▓▓▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▓▒               
▒▒▓▓▒▒▓▓▓▒▒▓▓▒▒▓▒▒▒▒▒▓▓▓▒▒   ▒      ▒▒   ▒▓▓▓▓▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▓▒                
▒▓▒▓▓▓▒▒▓▓▒▒▓▓▒▒▒▒▓▓▓▓▒    ▒▒▒▒▒     ▒▓▓▓▓▓▓▒▒▒▒▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒               
▒▓▒▒▓▓▒▓▓▒▒▓▒▒▒▓▒▒▒▒▓▓▓▓▓▒▒           ▒▓▓▓▓▓▓▓▓▒▒▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▓              
▒▓▒▒▓▓▒▒▒▓▓▒▒▓▓▓▓▒▒▓▓█▓▓▓▓▒▒▒▒▒     ▒▒▒▓▓▓▓▓█▓▓▓▓▒▓▒▒▒▒▒▒▒▒▒▒▒▒▒▒▓▒              
▒▓▒▒▓▓▒▒▒▒▓▓▓▒▒▓▓▓▓▓██████▓▒▒▒▒▒▒▒▒▒▒▒▒▒▓▓▓▓███▓▓▓▓▒▓▓▒▒▒▒▒▒▒▒▒▒▒▒▒               
▒▓▒▒▓▓▒▒▒▒▓▓▓▒▒▓▓▒▓████████▓▒ ▒▒▒▒▒▒▒▒ ▒▒▓███████▓▓▓▓▓▓▓▓▒▒▒▒▒▒▒▒▒▒               
▒▓▒▒▓▓▒▒▒▒▓▒▒▒▒▓▒▒▓█████████▓▒▒▒▒▒▒▒▒▒▓▓▓███████████▓▓▓▓▒▒▒▒▒▒▒▒▒▒▒▒              
▒▒▓▓▒▒▒▓▓▒▒▓▓▒▒▒▒▓▒▓▓███████████▓▓▒▒▓▓▓▓████████████▓█▓▒▓▓▓▓▒▒▒▒▒▒▒▒▒▒▓▒▒▓▒         
▒▒▒▓▓▒▒▓▓▓▓▓▓▓▒▒▒▓▒▓▓▓██████████▓▓▓▓▓▓▓▓██████████▓▓▓▓▒▒▒▓▓▓▓▓▒▒▒▒▒▓▓▓▓▓▓▒          
▒▓▓▓▓▓▓▓▓▓▓▓▒▒▒▓▓▓▓▓█████████▓▓▓▓▓▓▓▓▓████████▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▒▒▒            
▒▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓█▓▓▓▓▓▓▓▓▓█▓▓▓▓▓███████▓▓▓▓▓▓██▓▓▓▓▓▓▓▓                    
▒▓▓▓▓▓▓▓▓▓▓▓▓████▓▓▓▓▓█▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▒                   
▒▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓                   
▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓                  
▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▒                 
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓                 
▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▒                
▒▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓██▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓                
▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█                
▒▓▓▓▓▓▓▓▓▓▓▓██▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▒               
▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓               
▒▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▒              
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓              
▒▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓█▒             
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓             
▒▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓█▓▓▓▓▓▓▓▓▓▓▓▓▓▓                   