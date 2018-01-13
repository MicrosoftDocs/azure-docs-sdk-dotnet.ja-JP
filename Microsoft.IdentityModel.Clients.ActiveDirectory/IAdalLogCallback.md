<Type Name="IAdalLogCallback" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.IAdalLogCallback">
  <TypeSignature Language="C#" Value="public interface IAdalLogCallback" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAdalLogCallback" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.IAdalLogCallback" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAdalLogCallback" />
  <TypeSignature Language="F#" Value="type IAdalLogCallback = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b8981-101">ADAL をキャプチャするためのコールバックは、カスタム ログ スキームに記録します。</span><span class="sxs-lookup"><span data-stu-id="b8981-101">Callback for capturing ADAL logs to custom logging schemes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Log">
      <MemberSignature Language="C#" Value="public void Log (Microsoft.IdentityModel.Clients.ActiveDirectory.LogLevel level, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Log(valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.LogLevel level, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.IAdalLogCallback.Log(Microsoft.IdentityModel.Clients.ActiveDirectory.LogLevel,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Log (level As LogLevel, message As String)" />
      <MemberSignature Language="F#" Value="abstract member Log : Microsoft.IdentityModel.Clients.ActiveDirectory.LogLevel * string -&gt; unit" Usage="iAdalLogCallback.Log (level, message)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="level" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.LogLevel" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="level"><span data-ttu-id="b8981-102">ログ レベル</span><span class="sxs-lookup"><span data-stu-id="b8981-102">Log level</span></span></param>
        <param name="message"><span data-ttu-id="b8981-103">記録されるメッセージ</span><span class="sxs-lookup"><span data-stu-id="b8981-103">message to be logged</span></span></param>
        <summary>
            <span data-ttu-id="b8981-104">カスタム ログを実装するコールバック メソッド</span><span class="sxs-lookup"><span data-stu-id="b8981-104">Callback method to implement for custom logging</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>