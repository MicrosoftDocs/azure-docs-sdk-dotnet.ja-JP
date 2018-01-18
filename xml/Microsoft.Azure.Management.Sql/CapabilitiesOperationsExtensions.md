<Type Name="CapabilitiesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.CapabilitiesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CapabilitiesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CapabilitiesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.CapabilitiesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CapabilitiesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CapabilitiesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c32b1-101">CapabilitiesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="c32b1-101">Extension methods for CapabilitiesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByLocation">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.LocationCapabilities ListByLocation (this Microsoft.Azure.Management.Sql.ICapabilitiesOperations operations, string locationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.LocationCapabilities ListByLocation(class Microsoft.Azure.Management.Sql.ICapabilitiesOperations operations, string locationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.CapabilitiesOperationsExtensions.ListByLocation(Microsoft.Azure.Management.Sql.ICapabilitiesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByLocation (operations As ICapabilitiesOperations, locationId As String) As LocationCapabilities" />
      <MemberSignature Language="F#" Value="static member ListByLocation : Microsoft.Azure.Management.Sql.ICapabilitiesOperations * string -&gt; Microsoft.Azure.Management.Sql.Models.LocationCapabilities" Usage="Microsoft.Azure.Management.Sql.CapabilitiesOperationsExtensions.ListByLocation (operations, locationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.LocationCapabilities</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ICapabilitiesOperations" RefType="this" />
        <Parameter Name="locationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c32b1-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c32b1-102">The operations group for this extension method.</span></span>
            </param>
        <param name="locationId">
            <span data-ttu-id="c32b1-103">場所 id 機能を持つが取得されます。</span><span class="sxs-lookup"><span data-stu-id="c32b1-103">The location id whose capabilities are retrieved.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c32b1-104">指定された場所の使用可能な機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="c32b1-104">Gets the capabilities available for the specified location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByLocationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.LocationCapabilities&gt; ListByLocationAsync (this Microsoft.Azure.Management.Sql.ICapabilitiesOperations operations, string locationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.LocationCapabilities&gt; ListByLocationAsync(class Microsoft.Azure.Management.Sql.ICapabilitiesOperations operations, string locationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.CapabilitiesOperationsExtensions.ListByLocationAsync(Microsoft.Azure.Management.Sql.ICapabilitiesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByLocationAsync : Microsoft.Azure.Management.Sql.ICapabilitiesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.LocationCapabilities&gt;" Usage="Microsoft.Azure.Management.Sql.CapabilitiesOperationsExtensions.ListByLocationAsync (operations, locationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.CapabilitiesOperationsExtensions/&lt;ListByLocationAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.LocationCapabilities&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ICapabilitiesOperations" RefType="this" />
        <Parameter Name="locationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c32b1-105">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c32b1-105">The operations group for this extension method.</span></span>
            </param>
        <param name="locationId">
            <span data-ttu-id="c32b1-106">場所 id 機能を持つが取得されます。</span><span class="sxs-lookup"><span data-stu-id="c32b1-106">The location id whose capabilities are retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c32b1-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c32b1-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c32b1-108">指定された場所の使用可能な機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="c32b1-108">Gets the capabilities available for the specified location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>