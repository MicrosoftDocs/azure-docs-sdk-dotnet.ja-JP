<Type Name="IWithRouteTable" FullName="Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithRouteTable">
  <TypeSignature Language="C#" Value="public interface IWithRouteTable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRouteTable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithRouteTable" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRouteTable" />
  <TypeSignature Language="F#" Value="type IWithRouteTable = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="101e5-101">サブネットのステージでは、更新可能であり、サブネットに関連付けるルート テーブルを指定するのにまたは、既存の関連付けを削除します。</span><span class="sxs-lookup"><span data-stu-id="101e5-101">The stage of a subnet update allowing to specify a route table to associate with the subnet, or remove an existing association.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingRouteTable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithExistingRouteTable (Microsoft.Azure.Management.Network.Fluent.IRouteTable routeTable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithExistingRouteTable(class Microsoft.Azure.Management.Network.Fluent.IRouteTable routeTable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithRouteTable.WithExistingRouteTable(Microsoft.Azure.Management.Network.Fluent.IRouteTable)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingRouteTable (routeTable As IRouteTable) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingRouteTable : Microsoft.Azure.Management.Network.Fluent.IRouteTable -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate" Usage="iWithRouteTable.WithExistingRouteTable routeTable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="routeTable" Type="Microsoft.Azure.Management.Network.Fluent.IRouteTable" />
      </Parameters>
      <Docs>
        <param name="routeTable"><span data-ttu-id="101e5-102">関連付ける既存のルート テーブル。</span><span class="sxs-lookup"><span data-stu-id="101e5-102">An existing route table to associate.</span></span></param>
        <summary>
            <span data-ttu-id="101e5-103">サブネットに関連付ける既存のルート テーブルを指定します。</span><span class="sxs-lookup"><span data-stu-id="101e5-103">Specifies an existing route table to associate with the subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="101e5-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="101e5-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingRouteTable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithExistingRouteTable (string resourceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithExistingRouteTable(string resourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithRouteTable.WithExistingRouteTable(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingRouteTable (resourceId As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingRouteTable : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate" Usage="iWithRouteTable.WithExistingRouteTable resourceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceId"><span data-ttu-id="101e5-105">既存のルート テーブルのリソース ID です。</span><span class="sxs-lookup"><span data-stu-id="101e5-105">The resource ID of an existing route table.</span></span></param>
        <summary>
            <span data-ttu-id="101e5-106">サブネットに関連付ける既存のルート テーブルを指定します。</span><span class="sxs-lookup"><span data-stu-id="101e5-106">Specifies an existing route table to associate with the subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="101e5-107">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="101e5-107">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutRouteTable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithoutRouteTable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithoutRouteTable() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithRouteTable.WithoutRouteTable" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutRouteTable () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutRouteTable : unit -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate" Usage="iWithRouteTable.WithoutRouteTable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="101e5-108">存在する場合は、ルート テーブルとの関連付けを削除します。</span><span class="sxs-lookup"><span data-stu-id="101e5-108">Removes the association with a route table, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="101e5-109">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="101e5-109">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>