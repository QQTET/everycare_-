<template>
<div>
  <h2>내 정보</h2>
      <br>
    <table border="1" width="600px" cellpadding="15px" frame=void>
        <tr>
            <th id="id-line" width=20%>아이디</th>
            <td id="id-text" width=30%></td>
            <th id="pw-line" width=20%>비밀번호</th>
            <td id="pw-text" width=30%><button>비밀번호 변경</button></td>
        </tr>
        <tr>
            <th id="name-line">이름</th>
            <td width=30%></td>
            <th id="gen-line" width=20%>성별/나이</th>
            <td id="gen-text-line" width=30%></td>
        </tr>
        <tr>
            <th id="bir-line">생년월일</th>
            <td id="bir-text-line" colspan="3"></td>
        </tr>
        <tr>
            <th id="num-line">연락처</th>
            <td id="num-text-line" colspan="3"></td>
        </tr>
        <tr>
            <th id="mail-line">이메일</th>
            <td id="mail-text-line" colspan="3"></td>
        </tr>
        <tr>
            <th id="addr-line"><br><br>주소<br><br><br></th>
            <td id="addr-text-line" colspan="3"></td>   
        </tr>
        <tr>
           <th id="con-line"><br><br>계좌<br><br><br></th>
           <td id="con-text-line" colspan="3"></td> 
        </tr>
    </table>
    <br>
     <button id="ok-btn">확인</button>
     </div>
</template>

<script>
export default {

}
</script>

<style>
table {
    width: 100%;
    border:0;
    border-collapse:collapse;
  }
  th, td {
    border: solid 1px;
    
  }
  #id-line{
      border-left: none; 
      background-color: rgb(116, 231, 116); 
  }
  #pw-line, #gen-line{
    background-color: rgb(116, 231, 116);
  }
  #pw-text{  
    border-right: none;
  }
  #name-line, #bir-line, #num-line, #mail-line,
  #addr-line, #con-line{
    border-left: none;
    background-color: rgb(116, 231, 116);
  }

  #bir-text-line, #num-text-line, #gen-text-line, #mail-text-line, #addr-text-line, #con-text-line{
      border-right: none;
  }
  #ok-btn{
      margin: auto;
      display: block;
  }
</style>