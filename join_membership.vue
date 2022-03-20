<template>
<div>
  <h2>회원가입</h2>
        <hr>
       
        <table>
            <tr>
                <td>아이디</td><td><input type="text">&nbsp;<input type="button" value="중복검사"></td>
            </tr>
            <tr>
                <td>비밀번호</td><td><input type="password"></td>
            </tr>
            <tr>
                <td>비밀번호 확인</td><td><input type="text"></td>
            </tr>
            <tr>
                <td>이름</td><td><input type="text"></td>
            </tr>
            <tr>
                <td>성별</td><td><input type="radio">남 <input type="radio">여</td>
            </tr>
            <tr>
                <td>이메일</td><td><input type="text"> @ <input type="text" placeholder="직접입력">&nbsp;
                    <td>
                        <select size="1" id="email-addr">
                            <option>선택하세요</option>
                            <option>naver.com</option>
                            <option>google.co.kr</option>
                            <option>nate.com</option>
                            <option>daum.net</option>
                        </select>
                    </td>
            </tr>
            
           
            <tr>
                <td>생년월일</td>
                <td>               
                    <select>
                        <option>년</option>
                        <option>2016</option>
                        <option>2015</option>
                        <option>2014</option>
                        <option>2013</option>
                        <option>2012</option>
                        <option>2011</option>
                        <option>2010</option>
                        <option>2009</option>
                        <option>2008</option>
                        <option>2007</option>
                        <option>2006</option>
                        <option>2005</option>
                        <option>2004</option>
                        <option>2003</option>
                        <option>2002</option>
                        <option>2001</option>
                        <option>2000</option>
                        <option>1999</option>
                        <option>1998</option>
                        <option>1997</option>
                        <option>1996</option>
                    </select>
                    -
                    <select>
                        <option>월</option>
                        <option>1</option>
                        <option>2</option>
                        <option>3</option>
                        <option>4</option>
                        <option>5</option>
                        <option>6</option>
                        <option>7</option>
                        <option>8</option>
                        <option>9</option>
                        <option>10</option>
                        <option>11</option>
                        <option>12</option>
                    </select>
               
                -
               
                    <select>
                        <option>일</option>
                        <option>1</option>
                        <option>2</option>
                        <option>3</option>
                        <option>4</option>
                        <option>5</option>
                        <option>6</option>
                        <option>7</option>
                        <option>8</option>
                        <option>9</option>
                        <option>10</option>
                        <option>11</option>
                        <option>12</option>
                        <option>13</option>
                        <option>14</option>
                        <option>15</option>
                        <option>16</option>
                        <option>17</option>
                        <option>18</option>
                        <option>19</option>
                        <option>20</option>
                        <option>21</option>
                        <option>22</option>
                        <option>23</option>
                        <option>24</option>
                        <option>25</option>
                        <option>26</option>
                        <option>27</option>
                        <option>28</option>
                        <option>29</option>
                        <option>30</option>
                    </select>
                </td>
               
            
            </tr>      
            
            <tr>
                <td>우편번호</td><td><input type="text"> <input type="button" value="검색"> </td>
            </tr>
            <br>
            <tr>
                <td rowspan="2">주소</td><td><input type="text" id="addr-hold1"></td>
            </tr>
            <tr>
                <td><input type="text" id="addr-hold2"></td>
            </tr>
            <tr>
                <td>휴대폰</td>
                <td><select>
                    <option>010</option>
                    <option>011</option>
                    <option>018</option>
                    <option>019</option>
                </select> - <input type="text"> - <input type="text"></td>
                </tr>
                <tr>
                    <td rowspan="2">계좌</td><td><input type="text"></td><td><input type="button" value="은행찾기" id="bank-btn"></td>
                </tr>
                <tr>
                    <td><input type="text" id="bank-hold"></td>
                </tr>
        </table>
        <br>
          <button>등록</button>
          </div>
</template>

<script>
export default {

}
</script>

<style>
    #addr-hold1{
           width: 185px;
       }
       #addr-hold2{
           width: 185px;
       }
       #email-addr{
           position: relative;
           right: 75px;
       }
       #bank-btn{
           position: relative;
           right: 250px;
       }
       #bank-hold{
           width: 213px;
       }
</style>