# 方法名称

方法功能描述。例如：调用DescribeDBInstanceMonitor接口查询监控频率。

## 调试 

如果具备调试功能。例如：前往【[API Explorer]()】在线调试，API Explorer 提供在线调用 API、动态生成 SDK Example 代码和快速检索接口等能力，能显著降低使用云 API 的难度，强烈推荐使用。

## 请求参数 

|名称|类型|是否必选|示例值|描述|
|---|------|------|------|------|
|Action|String|是|DescribeDBInstanceMonitor|系统规定参数，取值：**DescribeDBInstanceMonitor**。

## 返回参数 

|名称|类型|示例值|描述|
|---|-----|------|-----|
|Period|String|60|监控的采集数据间隔，单位：秒。
|RequestId|String|30829FD4-1A84-4C2A-A625-2EADECB95CA3|请求ID。

## 示例

请求示例

``` {#request_demo}

http(s)://rds.aliyuncs.com/?Action=DescribeDBInstanceMonitor（给出实际产品的例子）
&DBInstanceId=rm-uf6wjk5xxxxxxx
&<公共请求参数>

```

正常返回示例

`XML` 格式

``` {#xml_return_success_demo}
<DescribeDBInstanceMonitorResponse>
  <period>60</period>
  <requestId>30829FD4-1A84-4C2A-A625-2EADECB95CA3</requestId>
</DescribeDBInstanceMonitorResponse>

```

`JSON` 格式

``` {#json_return_success_demo}
{
	"requestId":"30829FD4-1A84-4C2A-A625-2EADECB95CA3",
	"period":"60"
}
```

## 错误码

[查看本产品错误码]()
