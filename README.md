# BYRApiSet

## [BYRWechatShare](https://github.com/LeeLom/BYRApiSet/tree/master/BYRWechatShare)
对微信开放的Api进行了简单的二次封装，一句代码实现分享文字、图像、视频、连接等等。
</br>

分享文字

	[BYRWechatShare shareToWechatWithText:@"LeeLom大帅比 哈哈" type:0]; 

</br>

分享图片

	UIImage *image = [UIImage imageNamed:@"test"];
	UIImage *thumbImage = [UIImage imageNamed:@"test"];
	[BYRWechatShare shareToWechatWithImage:image thumbImage:thumbImage type:0];

</br>

分享歌曲

	UIImage *thumbImage = [UIImage imageNamed:@"test"];
	[BYRWechatShare shareToWechatWithMusicTitle:@"歌曲名"
	                              description:@"歌曲描述"
	                               thumbImage:thumbImage
	                                 musicUrl:@"www.baidu.com" //替换你的URL
	                             musicDataUrl:@"www.baidu.com" //替换你的URL
	                                     type:1];

</br>

分享连接

	[BYRWechatShare shareToWechatWithWebTitle:@"网页名字"
	                            description:@"网页描述"
	                             thumbImage:thumbImage
	                             webpageUrl:@"www.baidu.com"
	                                   type:1];

</br>
