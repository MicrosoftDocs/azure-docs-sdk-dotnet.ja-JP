<Type Name="IWithDestinationAddressPrefix&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithDestinationAddressPrefix&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithDestinationAddressPrefix&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDestinationAddressPrefix`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithDestinationAddressPrefix`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDestinationAddressPrefix(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithDestinationAddressPrefix&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="d90d3-101">WithAttach.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="d90d3-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="d90d3-102">移行先のアドレス プレフィックスを指定できるようにルート定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="d90d3-102">The stage of a route definition allowing to specify the destination address prefix.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDestinationAddressPrefix">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithNextHopType&lt;ParentT&gt; WithDestinationAddressPrefix (string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithNextHopType`1&lt;!ParentT&gt; WithDestinationAddressPrefix(string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithDestinationAddressPrefix`1.WithDestinationAddressPrefix(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDestinationAddressPrefix (cidr As String) As IWithNextHopType(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithDestinationAddressPrefix : string -&gt; Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithNextHopType&lt;'ParentT&gt;" Usage="iWithDestinationAddressPrefix.WithDestinationAddressPrefix cidr" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithNextHopType&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cidr"><span data-ttu-id="d90d3-103">CIDR 表記で表されるアドレス プレフィックスです。</span><span class="sxs-lookup"><span data-stu-id="d90d3-103">An address prefix expressed in the CIDR notation.</span></span></param>
        <summary>
            <span data-ttu-id="d90d3-104">ルートを適用する変換先のアドレス プレフィックスを指定します。</span><span class="sxs-lookup"><span data-stu-id="d90d3-104">Specifies the destination address prefix to apply the route to.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d90d3-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="d90d3-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>