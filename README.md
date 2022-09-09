# Vietnam local selector - JavaScript plugin

_Create HTML Select element for Vietnam province, district and ward._

+ DEMO: https://tappiweb.000webhostapp.com/

API: 
```html
<script src="https://pure-refuge-24132.herokuapp.com/assets/selectvietnam-78d0db86a154c518ae9695e1b78a15581401fe9e1b9dd6aa71c2872131892422.js"></script>
```



## Usage



HTML:
![image](https://user-images.githubusercontent.com/54675603/189052343-76d61839-07d8-4ca7-b95a-805d22028bcf.png)

```html
<form>
            <select name="ls_country" class="form-controlv height validate">
                <option value="Việt Nam" id="ls_vietnam">Việt Nam</option>
            </select>

            <input type="text" name="ls_province" id="txt_province" onchange="province()" placeholder="Province/City"
                list="dt_province">
            <datalist id="dt_province" style="display: none;">
                <option value="" hidden="">Province / City</option>
                <option value="An Giang" data-level="Tỉnh">An Giang
                </option>
                <option value="Bà Rịa - Vũng Tàu" data-level="Tỉnh">
                    Bà Rịa - Vũng Tàu</option>
                <option value="Bắc Giang" data-level="Tỉnh">Bắc
                    Giang</option>
                <option value="Bắc Kạn" data-level="Tỉnh">Bắc Kạn
                </option>
                <option value="Bạc Liêu" data-level="Tỉnh">Bạc Liêu
                </option>
                <option value="Bắc Ninh" data-level="Tỉnh">Bắc Ninh
                </option>
                <option value="Bến Tre" data-level="Tỉnh">Bến Tre
                </option>
                <option value="Bình Định" data-level="Tỉnh">Bình
                    Định</option>
                <option value="Bình Dương" data-level="Tỉnh">Bình
                    Dương</option>
                <option value="Bình Phước" data-level="Tỉnh">Bình
                    Phước</option>
                <option value="Bình Thuận" data-level="Tỉnh">Bình
                    Thuận</option>
                <option value="Cà Mau" data-level="Tỉnh">Cà Mau
                </option>
                <option value="Cần Thơ" data-level="Thành Phố">Cần
                    Thơ</option>
                <option value="Cao Bằng" data-level="Tỉnh">Cao Bằng
                </option>
                <option value="Đà Nẵng" data-level="Thành Phố">Đà
                    Nẵng</option>
                <option value="Đắk Lắk" data-level="Tỉnh">Đắk Lắk
                </option>
                <option value="Đắk Nông" data-level="Tỉnh">Đắk Nông
                </option>
                <option value="Điện Biên" data-level="Tỉnh">Điện
                    Biên</option>
                <option value="Đồng Nai" data-level="Tỉnh">Đồng Nai
                </option>
                <option value="Đồng Tháp" data-level="Tỉnh">Đồng
                    Tháp</option>
                <option value="Gia Lai" data-level="Tỉnh">Gia Lai
                </option>
                <option value="Hà Giang" data-level="Tỉnh">Hà Giang
                </option>
                <option value="Hà Nam" data-level="Tỉnh">Hà Nam
                </option>
                <option value="Hà Nội" data-level="Thành Phố">Hà Nội
                </option>
                <option value="Hà Tĩnh" data-level="Tỉnh">Hà Tĩnh
                </option>
                <option value="Hải Dương" data-level="Tỉnh">Hải
                    Dương</option>
                <option value="Hải Phòng" data-level="Thành Phố">Hải
                    Phòng</option>
                <option value="Hậu Giang" data-level="Tỉnh">Hậu
                    Giang</option>
                <option value="Hồ Chí Minh" data-level="Thành Phố">
                    Hồ Chí Minh</option>
                <option value="Hòa Bình" data-level="Tỉnh">Hòa Bình
                </option>
                <option value="Hưng Yên" data-level="Tỉnh">Hưng Yên
                </option>
                <option value="Khánh Hòa" data-level="Tỉnh">Khánh
                    Hòa</option>
                <option value="Kiên Giang" data-level="Tỉnh">Kiên
                    Giang</option>
                <option value="Kon Tum" data-level="Tỉnh">Kon Tum
                </option>
                <option value="Lai Châu" data-level="Tỉnh">Lai Châu
                </option>
                <option value="Lâm Đồng" data-level="Tỉnh">Lâm Đồng
                </option>
                <option value="Lạng Sơn" data-level="Tỉnh">Lạng Sơn
                </option>
                <option value="Lào Cai" data-level="Tỉnh">Lào Cai
                </option>
                <option value="Long An" data-level="Tỉnh">Long An
                </option>
                <option value="Nam Định" data-level="Tỉnh">Nam Định
                </option>
                <option value="Nghệ An" data-level="Tỉnh">Nghệ An
                </option>
                <option value="Ninh Bình" data-level="Tỉnh">Ninh
                    Bình</option>
                <option value="Ninh Thuận" data-level="Tỉnh">Ninh
                    Thuận</option>
                <option value="Phú Thọ" data-level="Tỉnh">Phú Thọ
                </option>
                <option value="Phú Yên" data-level="Tỉnh">Phú Yên
                </option>
                <option value="Quảng Bình" data-level="Tỉnh">Quảng
                    Bình</option>
                <option value="Quảng Nam" data-level="Tỉnh">Quảng
                    Nam</option>
                <option value="Quảng Ngãi" data-level="Tỉnh">Quảng
                    Ngãi</option>
                <option value="Quảng Ninh" data-level="Tỉnh">Quảng
                    Ninh</option>
                <option value="Quảng Trị" data-level="Tỉnh">Quảng
                    Trị</option>
                <option value="Sóc Trăng" data-level="Tỉnh">Sóc
                    Trăng</option>
                <option value="Sơn La" data-level="Tỉnh">Sơn La
                </option>
                <option value="Tây Ninh" data-level="Tỉnh">Tây Ninh
                </option>
                <option value="Thái Bình" data-level="Tỉnh">Thái
                    Bình</option>
                <option value="Thái Nguyên" data-level="Tỉnh">Thái
                    Nguyên</option>
                <option value="Thanh Hóa" data-level="Tỉnh">Thanh
                    Hóa</option>
                <option value="Thừa Thiên Huế" data-level="Tỉnh">
                    Thừa Thiên Huế</option>
                <option value="Tiền Giang" data-level="Tỉnh">Tiền
                    Giang</option>
                <option value="Trà Vinh" data-level="Tỉnh">Trà Vinh
                </option>
                <option value="Tuyên Quang" data-level="Tỉnh">Tuyên
                    Quang</option>
                <option value="Vĩnh Long" data-level="Tỉnh">Vĩnh
                    Long</option>
                <option value="Vĩnh Phúc" data-level="Tỉnh">Vĩnh
                    Phúc</option>
                <option value="Yên Bái" data-level="Tỉnh">Yên Bái
                </option>
            </datalist>

            <input type="text" name="ls_district" id="txt_district" onchange="district()" placeholder="District"
                list="dt_district">
            <datalist id="dt_district" style="display: none;">
            </datalist>

            <input type="text" name="ls_ward" id="txt_ward" placeholder="Ward" list="dt_ward">
            <datalist id="dt_ward" style="display: none;">
            </datalist>
        </form>
```
