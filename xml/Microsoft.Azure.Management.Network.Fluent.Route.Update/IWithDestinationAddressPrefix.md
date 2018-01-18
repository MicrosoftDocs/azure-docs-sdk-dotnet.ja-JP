<Type Name="IWithDestinationAddressPrefix" FullName="Microsoft.Azure.Management.Network.Fluent.Route.Update.IWithDestinationAddressPrefix">
  <TypeSignature Language="C#" Value="public interface IWithDestinationAddressPrefix" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDestinationAddressPrefix" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Route.Update.IWithDestinationAddressPrefix" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDestinationAddressPrefix" />
  <TypeSignature Language="F#" Value="type IWithDestinationAddressPrefix = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="45a6d-101">移行先のアドレス プレフィックスを変更する許可するルート更新の段階です。</span><span class="sxs-lookup"><span data-stu-id="45a6d-101">The stage of a route update allowing to modify the destination address prefix.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDestinationAddressPrefix">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate WithDestinationAddressPrefix (string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate WithDestinationAddressPrefix(string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Route.Update.IWithDestinationAddressPrefix.WithDestinationAddressPrefix(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDestinationAddressPrefix (cidr As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDestinationAddressPrefix : string -&gt; Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate" Usage="iWithDestinationAddressPrefix.WithDestinationAddressPrefix cidr" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cidr"><span data-ttu-id="45a6d-102">CIDR 表記で表されるアドレス プレフィックスです。</span><span class="sxs-lookup"><span data-stu-id="45a6d-102">An address prefix expressed in the CIDR notation.</span></span></param>
        <summary>
            <span data-ttu-id="45a6d-103">ルートを適用する変換先のアドレス プレフィックスを指定します。</span><span class="sxs-lookup"><span data-stu-id="45a6d-103">Specifies the destination address prefix to apply the route to.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="45a6d-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="45a6d-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>