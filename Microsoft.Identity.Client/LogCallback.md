<Type Name="LogCallback" FullName="Microsoft.Identity.Client.LogCallback">
  <TypeSignature Language="C#" Value="public delegate void LogCallback(Logger.LogLevel level, string message, bool containsPii);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed LogCallback extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.LogCallback" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Sub LogCallback(level As Logger.LogLevel, message As String, containsPii As Boolean)" />
  <TypeSignature Language="F#" Value="type LogCallback = delegate of Logger.LogLevel * string * bool -&gt; unit" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="level" Type="Microsoft.Identity.Client.Logger+LogLevel" />
    <Parameter Name="message" Type="System.String" />
    <Parameter Name="containsPii" Type="System.Boolean" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Void</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="level">メッセージのログ レベル</param>
    <param name="message">書式設定済みのログ メッセージ</param>
    <param name="containsPii">PII がログ メッセージに含まれるかどうかを示します。 Logger.PiiLoggingEnabled が false に設定されている場合は、この値は常に false にします。</param>
    <summary>
            により、開発者はログを使用するコールバック デリゲートは、一般的な方法でそれらを処理します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
</Type>