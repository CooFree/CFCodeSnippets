# CFCodeSnippets

文件目录
```~/Library/Developer/Xcode/UserData/CodeSnippets/```

<table>
<tr>
<th>简写</th>
<th>对应代码</th>
</tr>
<tr>
<td>mark1</td>
<td>#pragma mark - 1️⃣➢➢➢ <#mark#></td>
</tr>
<tr>
<td>blockproperty</td>
<td>@property (nonatomic,copy) <#returnType#> (^<#blockName#>)(<#parameterTypes#>);</td>
</tr>
<tr>
<td>pa</td>
<td>@property (nonatomic,assign) <#type#> <#name#></td>
</tr>

<tr>
<td>pc</td>
<td>@property (nonatomic, copy) <#type#> *<#name#></td>
</tr>

<tr>
<td>psr</td>
<td>@property (nonatomic, strong, readonly) <#type#> *<#name#></td>
</tr>

<tr>
<td>ps</td>
<td>@property (nonatomic, strong) <#type#> *<#name#></td>
</tr>

<tr>
<td>pw</td>
<td>@property (nonatomic, weak) <#type#> <#name#></td>
</tr>

<tr>
<td>sharedInstance</td>
<td>+ (instancetype)sharedInstance {
    static dispatch_once_t onceToken;
    static <#class name#> *instance = nil;
    dispatch_once(&onceToken,^{
        instance = [[super allocWithZone:NULL] init];
    });
    return instance;
}

+ (id)allocWithZone:(struct _NSZone *)zone{
    return [self sharedInstance];
}</td>
</tr>

<tr>
<td></td>
<td></td>
</tr>

<tr>
<td></td>
<td></td>
</tr>

<tr>
<td></td>
<td></td>
</tr>

</table>

