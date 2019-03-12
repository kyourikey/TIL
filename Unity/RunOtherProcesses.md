# RunOtherProcesses

-   Unityから他のプログラムを走らせる方法

### 開始処理

```csharp
var process = new Process();
process.StartInfo.FileName = "ファイルパス";
process.Start();
```

### 終了処理

```csharp
if (!process.HasExited)
{
  proc.CloseMainWindow();
}
proc.Close();
```

### C#(.Net)の機能です。

### 参考

<http://kconcon3.hatenablog.com/entry/2018/01/11/220000>
