function createPhoneNumber(numbers){
  let phoneNumber = "";
  
  numbers.splice(3,0," ");
  numbers.splice(7,0,"-");
  numbers.toString();
  
  for (let i=0; i<numbers.length; i++){
    if(i==0) { phoneNumber = phoneNumber + '('+ numbers[i]; }
    else if(i==2) { phoneNumber = phoneNumber + numbers[i] + ')'; }
    else phoneNumber = phoneNumber + numbers[i];      
  }
  return phoneNumber;
}
