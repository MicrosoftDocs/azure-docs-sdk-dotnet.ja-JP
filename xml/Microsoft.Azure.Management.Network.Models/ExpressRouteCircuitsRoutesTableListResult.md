<Type Name="ExpressRouteCircuitsRoutesTableListResult" FullName="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult">
  <TypeSignature Language="C#" Value="public class ExpressRouteCircuitsRoutesTableListResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteCircuitsRoutesTableListResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteCircuitsRoutesTableListResult" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitsRoutesTableListResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ceb3c-101">Express Route 回線 API に関連付けられている ListRoutesTable の応答。</span><span class="sxs-lookup"><span data-stu-id="ceb3c-101">Response for ListRoutesTable associated with the Express Route Circuits API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitsRoutesTableListResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ceb3c-102">ExpressRouteCircuitsRoutesTableListResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ceb3c-102">Initializes a new instance of the ExpressRouteCircuitsRoutesTableListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitsRoutesTableListResult (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable&gt; value = null, string nextLink = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable&gt; value, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional value As IList(Of ExpressRouteCircuitRoutesTable) = null, Optional nextLink As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult" Usage="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult (value, nextLink)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable&gt;" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="ceb3c-103">ルート テーブルの一覧。</span><span class="sxs-lookup"><span data-stu-id="ceb3c-103">The list of routes table.</span></span></param>
        <param name="nextLink"><span data-ttu-id="ceb3c-104">次の結果セットを取得する URL です。</span><span class="sxs-lookup"><span data-stu-id="ceb3c-104">The URL to get the next set of results.</span></span></param>
        <summary>
            <span data-ttu-id="ceb3c-105">ExpressRouteCircuitsRoutesTableListResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ceb3c-105">Initializes a new instance of the ExpressRouteCircuitsRoutesTableListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult.NextLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ceb3c-106">取得または次の結果セットを取得する URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="ceb3c-106">Gets or sets the URL to get the next set of results.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable&gt; Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As IList(Of ExpressRouteCircuitRoutesTable)" />
      <MemberSignature Language="F#" Value="member this.Value : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ceb3c-107">取得または、ルート テーブルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="ceb3c-107">Gets or sets the list of routes table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>