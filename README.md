# SJCombox
弹出视图使用说明：
    //初始化
    SJComboxView *comboxView = [[SJComboxView alloc] initWithFrame:CGRectMake(100, 100, 200, 44)];
    comboxView.dataSource = dataSource; //赋值
    [self.view addSubview:comboxView]; //添加视图
    comboxView.contentBlock = ^(NSString *string) {
        NSLog(@"%@",string); //选中数据。
    };
