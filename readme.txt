####  此owncloud针对校内用户，自动添加上服务器地址    

####   修改的位置位于com.owncloud.android.authenticaton.AuthenticatorActivity.java下 

将mHostUrlInput.setText(DisplayUtils.convertIdn(mServerInfo.mBaseUrl, false))改为mHostUrlInput.setText("http://cloud.swufe.edu.cn")


运行代码   在Android Studio中   直接导入xymail_dm  选择Import project(Eclipse ADT,Gradle,etc)