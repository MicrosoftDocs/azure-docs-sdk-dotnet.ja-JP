<Type Name="IWithSslType&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSslType&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSslType`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSslType(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithSslType&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="85b67-101">この定義をアタッチした後に戻るに親の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="85b67-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="85b67-102">SSL の型を指定するので、ホスト名 SSL のバインドの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="85b67-102">The stage of a hostname SSL binding definition allowing SSL type to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIpBasedSsl">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithIpBasedSsl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithIpBasedSsl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType`1.WithIpBasedSsl" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIpBasedSsl () As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithIpBasedSsl : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithSslType.WithIpBasedSsl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="85b67-103">使用して IP ベースの SSL です。</span><span class="sxs-lookup"><span data-stu-id="85b67-103">Uses IP based SSL.</span></span> <span data-ttu-id="85b67-104">1 つだけのホスト名にすることができますベースの SSL の IP アドレスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="85b67-104">Only one hostname can be bound to IP based SSL.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="85b67-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="85b67-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSniBasedSsl">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithSniBasedSsl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithSniBasedSsl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithSslType`1.WithSniBasedSsl" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSniBasedSsl () As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithSniBasedSsl : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithSslType.WithSniBasedSsl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="85b67-106">SSL を使用して Server Name Indication (SNI) に基づいています。</span><span class="sxs-lookup"><span data-stu-id="85b67-106">Uses Server Name Indication (SNI) based SSL.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="85b67-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="85b67-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>