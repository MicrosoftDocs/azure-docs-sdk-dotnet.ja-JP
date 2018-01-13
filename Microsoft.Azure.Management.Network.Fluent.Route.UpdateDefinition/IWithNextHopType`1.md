<Type Name="IWithNextHopType&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithNextHopType&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNextHopType&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNextHopType`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithNextHopType`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNextHopType(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithNextHopType&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="a0929-101">WithAttach.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="a0929-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="a0929-102">次ホップの種類の指定を許可するルート定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="a0929-102">The stage of a route definition allowing to specify the next hop type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNextHop">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithNextHop (Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType nextHopType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithNextHop(class Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType nextHopType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithNextHopType`1.WithNextHop(Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNextHop (nextHopType As RouteNextHopType) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNextHop : Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType -&gt; Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithNextHopType.WithNextHop nextHopType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextHopType" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType" />
      </Parameters>
      <Docs>
        <param name="nextHopType"><span data-ttu-id="a0929-103">ホップの種類。</span><span class="sxs-lookup"><span data-stu-id="a0929-103">A hop type.</span></span></param>
        <summary>
            <span data-ttu-id="a0929-104">次ホップの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="a0929-104">Specifies the next hop type.</span></span>
            <span data-ttu-id="a0929-105">仮想アプライアンスを使用するのには、.withNextHopToVirtualAppliance(String) を代わりに使用し、その IP アドレスを指定します。</span><span class="sxs-lookup"><span data-stu-id="a0929-105">To use a virtual appliance, use  .withNextHopToVirtualAppliance(String) instead and specify its IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a0929-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="a0929-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNextHopToVirtualAppliance">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithNextHopToVirtualAppliance (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithNextHopToVirtualAppliance(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithNextHopType`1.WithNextHopToVirtualAppliance(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNextHopToVirtualAppliance (ipAddress As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNextHopToVirtualAppliance : string -&gt; Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithNextHopType.WithNextHopToVirtualAppliance ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="a0929-107">既存の仮想アプライアンス (仮想マシン) の IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="a0929-107">An IP address of an existing virtual appliance (virtual machine).</span></span></param>
        <summary>
            <span data-ttu-id="a0929-108">移動するのには、次のホップに仮想アプライアンスの IP アドレスを指定します。</span><span class="sxs-lookup"><span data-stu-id="a0929-108">Specifies the IP address of the virtual appliance for the next hop to go to.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a0929-109">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="a0929-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>