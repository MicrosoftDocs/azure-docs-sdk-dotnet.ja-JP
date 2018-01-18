<Type Name="IPremiumEndpoint&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.PremiumEndpoint.IPremiumEndpoint&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IPremiumEndpoint&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPremiumEndpoint`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.PremiumEndpoint.IPremiumEndpoint`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPremiumEndpoint(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IPremiumEndpoint&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="dc521-101">この定義をアタッチした後に戻るに親 CDN プロファイルの更新の段階です。</span><span class="sxs-lookup"><span data-stu-id="dc521-101">The stage of the parent CDN profile update to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="dc521-102">CDN プロファイル Premium Verizon SKU がの原点を指定できるように、CDN プロファイル エンドポイント定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="dc521-102">The stage of the CDN profile endpoint definition allowing to specify the origin for CDN Profile with the Premium Verizon SKU.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPremiumOrigin">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithPremiumAttach&lt;ParentT&gt; WithPremiumOrigin (string originHostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithPremiumAttach`1&lt;!ParentT&gt; WithPremiumOrigin(string originHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.PremiumEndpoint.IPremiumEndpoint`1.WithPremiumOrigin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPremiumOrigin (originHostName As String) As IWithPremiumAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPremiumOrigin : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithPremiumAttach&lt;'ParentT&gt;" Usage="iPremiumEndpoint.WithPremiumOrigin originHostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithPremiumAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="originHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originHostName"><span data-ttu-id="dc521-103">配信元ホスト名です。</span><span class="sxs-lookup"><span data-stu-id="dc521-103">Origin host name.</span></span></param>
        <summary>
            <span data-ttu-id="dc521-104">CDN エンドポイントの配信元を指定します。</span><span class="sxs-lookup"><span data-stu-id="dc521-104">Specifies the origin of the CDN endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="dc521-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="dc521-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPremiumOrigin">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithPremiumAttach&lt;ParentT&gt; WithPremiumOrigin (string originName, string originHostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithPremiumAttach`1&lt;!ParentT&gt; WithPremiumOrigin(string originName, string originHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.PremiumEndpoint.IPremiumEndpoint`1.WithPremiumOrigin(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPremiumOrigin (originName As String, originHostName As String) As IWithPremiumAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPremiumOrigin : string * string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithPremiumAttach&lt;'ParentT&gt;" Usage="iPremiumEndpoint.WithPremiumOrigin (originName, originHostName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithPremiumAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="originName" Type="System.String" />
        <Parameter Name="originHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originName"><span data-ttu-id="dc521-106">配信元の名前です。</span><span class="sxs-lookup"><span data-stu-id="dc521-106">Name of the origin.</span></span></param>
        <param name="originHostName"><span data-ttu-id="dc521-107">配信元ホスト名です。</span><span class="sxs-lookup"><span data-stu-id="dc521-107">Origin host name.</span></span></param>
        <summary>
            <span data-ttu-id="dc521-108">CDN エンドポイントの配信元を指定します。</span><span class="sxs-lookup"><span data-stu-id="dc521-108">Specifies the origin of the CDN endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="dc521-109">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="dc521-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>