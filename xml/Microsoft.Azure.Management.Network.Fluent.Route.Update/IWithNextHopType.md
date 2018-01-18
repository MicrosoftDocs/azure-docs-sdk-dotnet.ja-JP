<Type Name="IWithNextHopType" FullName="Microsoft.Azure.Management.Network.Fluent.Route.Update.IWithNextHopType">
  <TypeSignature Language="C#" Value="public interface IWithNextHopType" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNextHopType" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Route.Update.IWithNextHopType" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNextHopType" />
  <TypeSignature Language="F#" Value="type IWithNextHopType = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="940a5-101">次ホップの種類を指定できるようにルート更新の段階です。</span><span class="sxs-lookup"><span data-stu-id="940a5-101">The stage of a route update allowing to specify the next hop type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNextHop">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate WithNextHop (Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType nextHopType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate WithNextHop(class Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType nextHopType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Route.Update.IWithNextHopType.WithNextHop(Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNextHop (nextHopType As RouteNextHopType) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNextHop : Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType -&gt; Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate" Usage="iWithNextHopType.WithNextHop nextHopType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextHopType" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType" />
      </Parameters>
      <Docs>
        <param name="nextHopType"><span data-ttu-id="940a5-102">ホップの種類。</span><span class="sxs-lookup"><span data-stu-id="940a5-102">A hop type.</span></span></param>
        <summary>
            <span data-ttu-id="940a5-103">次ホップの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="940a5-103">Specifies the next hop type.</span></span>
            <span data-ttu-id="940a5-104">仮想アプライアンスを使用するのには、.withNextHopToVirtualAppliance(String) を代わりに使用し、その IP アドレスを指定します。</span><span class="sxs-lookup"><span data-stu-id="940a5-104">To use a virtual appliance, use  .withNextHopToVirtualAppliance(String) instead and specify its IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="940a5-105">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="940a5-105">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNextHopToVirtualAppliance">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate WithNextHopToVirtualAppliance (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate WithNextHopToVirtualAppliance(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Route.Update.IWithNextHopType.WithNextHopToVirtualAppliance(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNextHopToVirtualAppliance (ipAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNextHopToVirtualAppliance : string -&gt; Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate" Usage="iWithNextHopType.WithNextHopToVirtualAppliance ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="940a5-106">既存の仮想アプライアンス (仮想マシン) の IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="940a5-106">An IP address of an existing virtual appliance (virtual machine).</span></span></param>
        <summary>
            <span data-ttu-id="940a5-107">移動するのには、次のホップに仮想アプライアンスの IP アドレスを指定します。</span><span class="sxs-lookup"><span data-stu-id="940a5-107">Specifies the IP address of the virtual appliance for the next hop to go to.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="940a5-108">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="940a5-108">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>