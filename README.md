# Vietnam local selector - JavaScript plugin

_Create HTML Select element for Vietnam province, district and ward._

+ DEMO: https://tappiweb.000webhostapp.com/

API JS: 
```html
    <script src="https://tappiweb.000webhostapp.com/selectvietnam.js"></script>
```



## Usage



#### HTML:
![image](https://user-images.githubusercontent.com/54675603/189052343-76d61839-07d8-4ca7-b95a-805d22028bcf.png)

```html
        <form>
            <label id="vietnam_local_select_error" style="color: red;"></label>
            <input type="text" name="ls_country" id="txt_country" onclick="setvaluecountry()" onchange="country()" placeholder="Country" list="dt_country">
                <datalist id="dt_country" style="display: none;">
                    <option value="Việt Nam">Việt Nam</option>
                    <option value="Campuchia">Campuchia</option>
                    <option value="Lào">Lào</option>
                    <option value="Thái Lan">Thái Lan</option>
                    <option value="Myanmar">Myanmar</option>
                    <option value="Malaysia">Malaysia</option>
                    <option value="Singapore">Singapore</option>
                    <option value="Indonesia">Indonesia</option>
                    <option value="Brunei">Brunei</option>
                    <option value="Philippines">Philippines</option>
                    <option value="Đông Timor">Đông Timor</option>
                    <option value="Trung Quốc">Trung Quốc</option>
                    <option value="Nhật Bản">Nhật Bản</option>
                    <option value="Mông Cổ">Mông Cổ</option>
                    <option value="Hàn Quốc">Hàn Quốc</option>
                    <option value="CHDCND Triều Tiên">CHDCND Triều Tiên</option>
                    <option value="Đài Loan">Đài Loan</option>
                    <option value="Hong Kong">Hong Kong</option>
                    <option value="Macau">Macau</option>
                    <option value="Ấn Độ">Ấn Độ</option>
                    <option value="Pakistan">Pakistan</option>
                    <option value="Bangladesh">Bangladesh</option>
                    <option value="Nepal">Nepal</option>
                    <option value="Bhutan">Bhutan</option>
                    <option value="Sri Lanka">Sri Lanka</option>
                    <option value="Maldives">Maldives</option>
                    <option value="British Indian Ocean Territory">British Indian Ocean Territory</option>
                    <option value="Afghanistan">Afghanistan</option>
                    <option value="Kazakhstan">Kazakhstan</option>
                    <option value="Uzbekistan">Uzbekistan</option>
                    <option value="Turkmenistan">Turkmenistan</option>
                    <option value="Tajikistan">Tajikistan</option>
                    <option value="Kyrgyzstan">Kyrgyzstan</option>
                    <option value="Iran">Iran</option>
                    <option value="Iraq">Iraq</option>
                    <option value="Saudi Arabia">Saudi Arabia</option>
                    <option value="Kuwait">Kuwait</option>
                    <option value="Qatar">Qatar</option>
                    <option value="Bahrain">Bahrain</option>
                    <option value="Palestine">Palestine</option>
                    <option value="Israel">Israel</option>
                    <option value="Các tiểu vương quốc Ả Rập thống nhất">Các tiểu vương quốc Ả Rập thống nhất</option>
                    <option value="Oman">Oman</option>
                    <option value="Yemen">Yemen</option>
                    <option value="Jordan">Jordan</option>
                    <option value="Syria">Syria</option>
                    <option value="Lebanon">Lebanon</option>
                    <option value="Turkey">Turkey</option>
                    <option value="Cyprus">Cyprus</option>
                    <option value="Northern Cyprus">Northern Cyprus</option>
                    <option value="Akrotiri và Dhekelia">Akrotiri và Dhekelia</option>
                    <option value="Azerbaijan">Azerbaijan</option>
                    <option value="Armenia">Armenia</option>
                    <option value="Gruzia">Gruzia</option>
                    <option value="Abkhazia">Abkhazia</option>
                    <option value="Nam Ossetia">Nam Ossetia</option>
                    <option value="Nagorno-Karabakh">Nagorno-Karabakh</option>
                    <option value="Thụy Điển">Thụy Điển</option>
                    <option value="Phần Lan">Phần Lan</option>
                    <option value="Na Uy">Na Uy</option>
                    <option value="Estonia">Estonia</option>
                    <option value="Latvia">Latvia</option>
                    <option value="Litva">Litva</option>
                    <option value="Đan Mạch">Đan Mạch</option>
                    <option value="Vương quốc Liên hiệp Anh và Bắc Ireland">Vương quốc Liên hiệp Anh và Bắc Ireland</option>
                    <option value="Ireland">Ireland</option>
                    <option value="Iceland">Iceland</option>
                    <option value="Quần đảo Faroe">Quần đảo Faroe</option>
                    <option value="Đảo Man">Đảo Man</option>
                    <option value="Jersey">Jersey</option>
                    <option value="Guernsey">Guernsey</option>
                    <option value="Svalbard">Svalbard</option>
                    <option value="Quần đảo Åland">Quần đảo Åland</option>
                    <option value="Đức">Đức</option>
                    <option value="Pháp">Pháp</option>
                    <option value="Hà Lan">Hà Lan</option>
                    <option value="Bỉ">Bỉ</option>
                    <option value="Thụy Sĩ">Thụy Sĩ</option>
                    <option value="Áo">Áo</option>
                    <option value="Luxembourg">Luxembourg</option>
                    <option value="Liechtenstein">Liechtenstein</option>
                    <option value="Monaco">Monaco</option>
                    <option value="Tây Ban Nha">Tây Ban Nha</option>
                    <option value="Bồ Đào Nha">Bồ Đào Nha</option>
                    <option value="Andorra">Andorra</option>
                    <option value="Gibraltar">Gibraltar</option>
                    <option value="Italy">Italy</option>
                    <option value="San Marino">San Marino</option>
                    <option value="Vatican">Vatican</option>
                    <option value="Malta">Malta</option>
                    <option value="Slovenia">Slovenia</option>
                    <option value="Croatia">Croatia</option>
                    <option value="Bosnia và Herzegovina">Bosnia và Herzegovina</option>
                    <option value="Montenegro">Montenegro</option>
                    <option value="Serbia">Serbia</option>
                    <option value="Kosovo">Kosovo</option>
                    <option value="Albania">Albania</option>
                    <option value="Hy Lạp">Hy Lạp</option>
                    <option value="Cộng hòa Macedonia">Cộng hòa Macedonia</option>
                    <option value="Nga">Nga</option>
                    <option value="Ukraine">Ukraine</option>
                    <option value="Ba Lan">Ba Lan</option>
                    <option value="Belarus">Belarus</option>
                    <option value="Moldova">Moldova</option>
                    <option value="Transnistria">Transnistria</option>
                    <option value="Cộng hòa Séc">Cộng hòa Séc</option>
                    <option value="Slovakia">Slovakia</option>
                    <option value="Hungary">Hungary</option>
                    <option value="Romania">Romania</option>
                    <option value="Bulgaria">Bulgaria</option>
                    <option value="Canada">Canada</option>
                    <option value="Hoa Kỳ">Hoa Kỳ</option>
                    <option value="Greenland">Greenland</option>
                    <option value="Saint Pierre và Miquelon">Saint Pierre và Miquelon</option>
                    <option value="Bermuda">Bermuda</option>
                    <option value="Mexico">Mexico</option>
                    <option value="Belize">Belize</option>
                    <option value="Guatemala">Guatemala</option>
                    <option value="El Salvador">El Salvador</option>
                    <option value="Honduras">Honduras</option>
                    <option value="Nicaragua">Nicaragua</option>
                    <option value="Costa Rica">Costa Rica</option>
                    <option value="Panama">Panama</option>
                    <option value="Brazil">Brazil</option>
                    <option value="Argentina">Argentina</option>
                    <option value="Uruguay">Uruguay</option>
                    <option value="Paraguay">Paraguay</option>
                    <option value="Chile">Chile</option>
                    <option value="Bolivia">Bolivia</option>
                    <option value="Peru">Peru</option>
                    <option value="Ecuador">Ecuador</option>
                    <option value="Colombia">Colombia</option>
                    <option value="Venezuela">Venezuela</option>
                    <option value="Suriname">Suriname</option>
                    <option value="Guyana">Guyana</option>
                    <option value="French Guiana">French Guiana</option>
                    <option value="Quần đảo Falkland">Quần đảo Falkland</option>
                    <option value="Quần đảo Nam Georgia và Nam Sandwich">Quần đảo Nam Georgia và Nam Sandwich</option>
                    <option value="Cuba">Cuba</option>
                    <option value="Jamaica">Jamaica</option>
                    <option value="Haiti">Haiti</option>
                    <option value="Cộng hòa Dominican">Cộng hòa Dominican</option>
                    <option value="Quần đảo Cayman">Quần đảo Cayman</option>
                    <option value="Puerto Rico">Puerto Rico</option>
                    <option value="Quần đảo Virgin thuộc Mỹ">Quần đảo Virgin thuộc Mỹ</option>
                    <option value="Quần đảo Virgin thuộc Anh">Quần đảo Virgin thuộc Anh</option>
                    <option value="The Bahamas">The Bahamas</option>
                    <option value="Quần đảo Turks và Caicos">Quần đảo Turks và Caicos</option>
                    <option value="Saint Kitts và Nevis">Saint Kitts và Nevis</option>
                    <option value="Anguilla">Anguilla</option>
                    <option value="Saint Barthélemy">Saint Barthélemy</option>
                    <option value="Montserrat">Montserrat</option>
                    <option value="Saba">Saba</option>
                    <option value="Sint Eustatius">Sint Eustatius</option>
                    <option value="Dominica">Dominica</option>
                    <option value="Grenada">Grenada</option>
                    <option value="Barbados">Barbados</option>
                    <option value="Saint Vincent và Grenadines">Saint Vincent và Grenadines</option>
                    <option value="Antigua và Barbuda">Antigua và Barbuda</option>
                    <option value="Saint Lucia">Saint Lucia</option>
                    <option value="Trinidad và Tobago">Trinidad và Tobago</option>
                    <option value="Aruba">Aruba</option>
                    <option value="Bonaire">Bonaire</option>
                    <option value="Curaçao">Curaçao</option>
                    <option value="Saint Martin">Saint Martin</option>
                    <option value="Sint Maarten">Sint Maarten</option>
                    <option value="Martinique">Martinique</option>
                    <option value="Guadeloupe">Guadeloupe</option>
                    <option value="Ai Cập">Ai Cập</option>
                    <option value="Libya">Libya</option>
                    <option value="Tunisia">Tunisia</option>
                    <option value="Algeria">Algeria</option>
                    <option value="Maroc">Maroc</option>
                    <option value="Tây Sahara">Tây Sahara</option>
                    <option value="Sudan">Sudan</option>
                    <option value="Nam Phi">Nam Phi</option>
                    <option value="Lesotho">Lesotho</option>
                    <option value="Swaziland">Swaziland</option>
                    <option value="Namibia">Namibia</option>
                    <option value="Botswana">Botswana</option>
                    <option value="Mauritania">Mauritania</option>
                    <option value="Mali">Mali</option>
                    <option value="Niger">Niger</option>
                    <option value="Nigeria">Nigeria</option>
                    <option value="Senegal">Senegal</option>
                    <option value="Gambia">Gambia</option>
                    <option value="Guinea">Guinea</option>
                    <option value="Guinea-Bissau">Guinea-Bissau</option>
                    <option value="Cape Verde">Cape Verde</option>
                    <option value="Sierra Leone">Sierra Leone</option>
                    <option value="Liberia">Liberia</option>
                    <option value="Côte d'Ivoire">Côte d'Ivoire</option>
                    <option value="Burkina Faso">Burkina Faso</option>
                    <option value="Ghana">Ghana</option>
                    <option value="Togo">Togo</option>
                    <option value="Benin">Benin</option>
                    <option value="Saint Helena, Ascension và Tristan da Cunha">Saint Helena, Ascension và Tristan da Cunha</option>
                    <option value="Tchad">Tchad</option>
                    <option value="Cộng hòa Trung Phi">Cộng hòa Trung Phi</option>
                    <option value="Cameroon">Cameroon</option>
                    <option value="Cộng hòa Dân chủ Congo">Cộng hòa Dân chủ Congo</option>
                    <option value="Cộng hòa Congo">Cộng hòa Congo</option>
                    <option value="Gabon">Gabon</option>
                    <option value="Guinea Xích Đạo">Guinea Xích Đạo</option>
                    <option value="São Tomé và Princípe">São Tomé và Princípe</option>
                    <option value="Angola">Angola</option>
                    <option value="Nam Sudan">Nam Sudan</option>
                    <option value="Ethiopia">Ethiopia</option>
                    <option value="Eritrea">Eritrea</option>
                    <option value="Djibouti">Djibouti</option>
                    <option value="Somalia">Somalia</option>
                    <option value="Somaliland">Somaliland</option>
                    <option value="Uganda">Uganda</option>
                    <option value="Rwanda">Rwanda</option>
                    <option value="Burundi">Burundi</option>
                    <option value="Kenya">Kenya</option>
                    <option value="Tanzania">Tanzania</option>
                    <option value="Malawi">Malawi</option>
                    <option value="Mozambique">Mozambique</option>
                    <option value="Zambia">Zambia</option>
                    <option value="Zimbabwe">Zimbabwe</option>
                    <option value="Madagascar">Madagascar</option>
                    <option value="Comoros">Comoros</option>
                    <option value="Seychelles">Seychelles</option>
                    <option value="Mauritius">Mauritius</option>
                    <option value="Réunion">Réunion</option>
                    <option value="Mayotte">Mayotte</option>
                    <option value="Australia">Australia</option>
                    <option value="New Zealand">New Zealand</option>
                    <option value="Đảo Norfolk">Đảo Norfolk</option>
                    <option value="Đảo Christmas">Đảo Christmas</option>
                    <option value="Quần đảo Cocos (Keeling)">Quần đảo Cocos (Keeling)</option>
                    <option value="Papua New Guinea">Papua New Guinea</option>
                    <option value="Palau">Palau</option>
                    <option value="Quần đảo Solomon">Quần đảo Solomon</option>
                    <option value="Vanuatu">Vanuatu</option>
                    <option value="Fiji">Fiji</option>
                    <option value="New Caledonia">New Caledonia</option>
                    <option value="Liên bang Micronesia">Liên bang Micronesia</option>
                    <option value="Kiribati">Kiribati</option>
                    <option value="Quần đảo Marshall">Quần đảo Marshall</option>
                    <option value="Nauru">Nauru</option>
                    <option value="Quần đảo Bắc Mariana">Quần đảo Bắc Mariana</option>
                    <option value="Guam">Guam</option>
                    <option value="Tuvalu">Tuvalu</option>
                    <option value="Tonga">Tonga</option>
                    <option value="Samoa">Samoa</option>
                    <option value="Samoa thuộc Mỹ">Samoa thuộc Mỹ</option>
                    <option value="Polynesia thuộc Pháp">Polynesia thuộc Pháp</option>
                    <option value="Wallis và Futuna">Wallis và Futuna</option>
                    <option value="Quần đảo Cook">Quần đảo Cook</option>
                    <option value="Niue">Niue</option>
                    <option value="Tokelau">Tokelau</option>
                    <option value="Quần đảo Pitcairn">Quần đảo Pitcairn</option>
                </datalist>

            <input type="text" name="ls_province" id="txt_province" onclick="setvalueprovince()" onchange="province()" placeholder="Province/City" list="dt_province">
            <datalist id="dt_province"  style="display: none;">
            </datalist>

            <input type="text" name="ls_district" id="txt_district"onclick="setvaluedistrict()" onchange="district()" placeholder="District" list="dt_district">
            <datalist id="dt_district" style="display: none;">
            </datalist>

            <input type="text" name="ls_ward" id="txt_ward" onclick="setvalueward()" placeholder="Ward" list="dt_ward">
            <datalist id="dt_ward" style="display: none;">
            </datalist>
        </form>
```
