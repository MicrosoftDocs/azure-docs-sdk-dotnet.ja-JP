<Type Name="IWithHostname&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithHostname&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithHostname&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithHostname`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithHostname`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithHostname(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithHostname&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="a1b64-101">この定義をアタッチした後に戻るに親の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="a1b64-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="a1b64-102">指定するホスト名を許可するホスト名の SSL バインディング定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="a1b64-102">The stage of a hostname SSL binding definition allowing hostname to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ForHostname">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithCertificate&lt;ParentT&gt; ForHostname (string hostname);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithCertificate`1&lt;!ParentT&gt; ForHostname(string hostname) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithHostname`1.ForHostname(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ForHostname (hostname As String) As IWithCertificate(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ForHostname : string -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithCertificate&lt;'ParentT&gt;" Usage="iWithHostname.ForHostname hostname" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithCertificate&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostname" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostname"><span data-ttu-id="a1b64-103">naked ホスト名、"www"を除外します。</span><span class="sxs-lookup"><span data-stu-id="a1b64-103">The naked hostname, excluding "www".</span></span> <span data-ttu-id="a1b64-104">使用されます。</span><span class="sxs-lookup"><span data-stu-id="a1b64-104">But use .</span></span> <span data-ttu-id="a1b64-105">プレフィックス ワイルド カードの証明書の順序を入力します。</span><span class="sxs-lookup"><span data-stu-id="a1b64-105">prefix for wild card typed certificate order.</span></span></param>
        <summary>
            <span data-ttu-id="a1b64-106">SSL 証明書をバインドするホスト名を指定します。</span><span class="sxs-lookup"><span data-stu-id="a1b64-106">Specifies the hostname to bind SSL certificate to.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a1b64-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="a1b64-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>