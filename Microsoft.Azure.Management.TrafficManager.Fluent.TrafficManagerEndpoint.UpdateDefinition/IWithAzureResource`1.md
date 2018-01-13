<Type Name="IWithAzureResource&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAzureResource&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAzureResource&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAzureResource`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAzureResource`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAzureResource(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAzureResource&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="448fe-101">WithAttach.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="448fe-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="448fe-102">Traffic manager プロファイルをターゲットの Azure リソースの ID を指定できるように Azure エンドポイント定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="448fe-102">The stage of the traffic manager profile Azure endpoint definition allowing to specify the ID of the target Azure resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToResourceId">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;ParentT&gt; ToResourceId (string resourceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; ToResourceId(string resourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAzureResource`1.ToResourceId(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToResourceId (resourceId As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToResourceId : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAzureResource.ToResourceId resourceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceId"><span data-ttu-id="448fe-103">Azure のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="448fe-103">The Azure resource id.</span></span></param>
        <summary>
            <span data-ttu-id="448fe-104">Azure のリソースのリソース ID を指定します。</span><span class="sxs-lookup"><span data-stu-id="448fe-104">Specifies the resource ID of an Azure resource.</span></span>
            <span data-ttu-id="448fe-105">サポートされている Azure リソースとは、クラウド サービス、web アプリまたはパブリック ip です。</span><span class="sxs-lookup"><span data-stu-id="448fe-105">supported Azure resources are cloud service, web app or public ip.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="448fe-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="448fe-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>