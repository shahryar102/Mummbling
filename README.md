# Mummbling
function accum(s){
  result=""
  for(let i=0;i<s.length;i++){
    for(let j=0;j<i+1;j++){
      if(j==0){result=result+s.charAt(i).toUpperCase()}
      else{result=result+s.charAt(i).toLowerCase()}
    }
    if (i==s.length-1){break;}
    result=result+"-"
  }
  
  console.log(result); return result;
}
accum('rtnrthFT')
