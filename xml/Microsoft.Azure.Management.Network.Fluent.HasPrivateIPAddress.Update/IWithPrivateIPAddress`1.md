<Type Name="IWithPrivateIPAddress&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Update.IWithPrivateIPAddress&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithPrivateIPAddress&lt;ReturnT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrivateIPAddress`1&lt;ReturnT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Update.IWithPrivateIPAddress`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrivateIPAddress(Of ReturnT)" />
  <TypeSignature Language="F#" Value="type IWithPrivateIPAddress&lt;'ReturnT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ReturnT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ReturnT"><span data-ttu-id="bd1e0-101">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="bd1e0-101">The next stage of the update.</span></span></typeparam>
    <summary>
            <span data-ttu-id="bd1e0-102">プライベート IP アドレスの変更を許可する更新プログラムの段階です。</span><span class="sxs-lookup"><span data-stu-id="bd1e0-102">The stage of an update allowing to modify the private IP address.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrivateIPAddressDynamic">
      <MemberSignature Language="C#" Value="public ReturnT WithPrivateIPAddressDynamic ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithPrivateIPAddressDynamic() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Update.IWithPrivateIPAddress`1.WithPrivateIPAddressDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateIPAddressDynamic () As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateIPAddressDynamic : unit -&gt; 'ReturnT" Usage="iWithPrivateIPAddress.WithPrivateIPAddressDynamic " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bd1e0-103">動的なプライベート IP アドレスの割り当て、関連付けられているサブネット内で有効にします。</span><span class="sxs-lookup"><span data-stu-id="bd1e0-103">Enables dynamic private IP address allocation within the associated subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="bd1e0-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="bd1e0-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPrivateIPAddressStatic">
      <MemberSignature Language="C#" Value="public ReturnT WithPrivateIPAddressStatic (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithPrivateIPAddressStatic(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Update.IWithPrivateIPAddress`1.WithPrivateIPAddressStatic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateIPAddressStatic (ipAddress As String) As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateIPAddressStatic : string -&gt; 'ReturnT" Usage="iWithPrivateIPAddress.WithPrivateIPAddressStatic ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="bd1e0-105">関連付けられているプライベート IP の範囲内の静的 IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="bd1e0-105">A static IP address within the associated private IP range.</span></span></param>
        <summary>
            <span data-ttu-id="bd1e0-106">関連付けられているサブネット内にある指定の static のプライベート IP アドレスを割り当てます。</span><span class="sxs-lookup"><span data-stu-id="bd1e0-106">Assigns the specified static private IP address within the associated subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="bd1e0-107">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="bd1e0-107">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>