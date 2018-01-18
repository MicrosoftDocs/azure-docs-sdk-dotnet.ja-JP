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
    <param name="level"><span data-ttu-id="21255-101">メッセージのログ レベル</span><span class="sxs-lookup"><span data-stu-id="21255-101">Log level of the message</span></span></param>
    <param name="message"><span data-ttu-id="21255-102">書式設定済みのログ メッセージ</span><span class="sxs-lookup"><span data-stu-id="21255-102">Pre-formatted log message</span></span></param>
    <param name="containsPii"><span data-ttu-id="21255-103">PII がログ メッセージに含まれるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="21255-103">Indicates if the log message contains PII.</span></span> <span data-ttu-id="21255-104">Logger.PiiLoggingEnabled が false に設定されている場合は、この値は常に false にします。</span><span class="sxs-lookup"><span data-stu-id="21255-104">If Logger.PiiLoggingEnabled is set to false then this value is always false.</span></span></param>
    <summary>
            <span data-ttu-id="21255-105">により、開発者はログを使用するコールバック デリゲートは、一般的な方法でそれらを処理します。</span><span class="sxs-lookup"><span data-stu-id="21255-105">Callback delegate that allows the developer to consume logs handle them in a custom manner.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
</Type>