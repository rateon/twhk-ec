# eccube基本的なメモ

*コメントアウトで規約スルー*  
data/class/pages/entry/LC_Page_Entry.php  
// PC時は規約ページからの遷移でなければエラー画面へ遷移する  
//if ($this->lfCheckReferer() === false) {  
//    SC_Utils_Ex::sfDispSiteError(PAGE_ERROR, '', true);  
//}  
//SC_Helper_Customer_Ex::sfCustomerEntryParam($objFormParam);  
//$objFormParam->setParam($_POST);  

*SUBMIT 画像処理解除*  
html/js/eccube.js  

*form Entry入力一覧*  
data/Smarty/templates/default/frontparts/form_personal_input.tpl  
data/Smarty/templates/default/frontparts/form_personal_confirm.tpl

*HEAD設定*  
data/Smarty/templates/default/site_frame.tpl

*郵便番号DB登録*
Zip アーカイブDL
http://svn.ec-cube.net/open_trac/changeset/21892
ファイルを配置
data/class/pages/admin/basis/LC_Page_Admin_Basis_ZipInstall.php

手動登録

*会員フォーム必須項目削除*

/data/Smarty/templates/default/frontparts/form_personal_input.tpl
/data/class/helper/SC_Helper_Customer.php

*エラーメッセージ*
data/class/SC_CheckError.php

