<Type Name="ExpressRouteCircuitRoutesTable" FullName="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable">
  <TypeSignature Language="C#" Value="public class ExpressRouteCircuitRoutesTable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteCircuitRoutesTable extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteCircuitRoutesTable" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitRoutesTable = class" />
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
            <span data-ttu-id="9b4ec-101">ExpressRouteCircuit に関連付けられているルート テーブル</span><span class="sxs-lookup"><span data-stu-id="9b4ec-101">The routes table associated with the ExpressRouteCircuit</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitRoutesTable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable.#ctor" />
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
            <span data-ttu-id="9b4ec-102">ExpressRouteCircuitRoutesTable クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9b4ec-102">Initializes a new instance of the ExpressRouteCircuitRoutesTable class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitRoutesTable (string network = null, string nextHop = null, string locPrf = null, Nullable&lt;int&gt; weight = null, string path = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string network, string nextHop, string locPrf, valuetype System.Nullable`1&lt;int32&gt; weight, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable.#ctor(System.String,System.String,System.String,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional network As String = null, Optional nextHop As String = null, Optional locPrf As String = null, Optional weight As Nullable(Of Integer) = null, Optional path As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable : string * string * string * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable" Usage="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable (network, nextHop, locPrf, weight, path)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="network" Type="System.String" />
        <Parameter Name="nextHop" Type="System.String" />
        <Parameter Name="locPrf" Type="System.String" />
        <Parameter Name="weight" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="network"><span data-ttu-id="9b4ec-103">ネットワーク</span><span class="sxs-lookup"><span data-stu-id="9b4ec-103">network</span></span></param>
        <param name="nextHop"><span data-ttu-id="9b4ec-104">次ホップ</span><span class="sxs-lookup"><span data-stu-id="9b4ec-104">nextHop</span></span></param>
        <param name="locPrf"><span data-ttu-id="9b4ec-105">locPrf</span><span class="sxs-lookup"><span data-stu-id="9b4ec-105">locPrf</span></span></param>
        <param name="weight"><span data-ttu-id="9b4ec-106">太さ。</span><span class="sxs-lookup"><span data-stu-id="9b4ec-106">weight.</span></span></param>
        <param name="path"><span data-ttu-id="9b4ec-107">パス</span><span class="sxs-lookup"><span data-stu-id="9b4ec-107">path</span></span></param>
        <summary>
            <span data-ttu-id="9b4ec-108">ExpressRouteCircuitRoutesTable クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9b4ec-108">Initializes a new instance of the ExpressRouteCircuitRoutesTable class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocPrf">
      <MemberSignature Language="C#" Value="public string LocPrf { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocPrf" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable.LocPrf" />
      <MemberSignature Language="VB.NET" Value="Public Property LocPrf As String" />
      <MemberSignature Language="F#" Value="member this.LocPrf : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable.LocPrf" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="locPrf")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9b4ec-109">取得または設定 locPrf</span><span class="sxs-lookup"><span data-stu-id="9b4ec-109">Gets or sets locPrf</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Network">
      <MemberSignature Language="C#" Value="public string Network { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Network" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable.Network" />
      <MemberSignature Language="VB.NET" Value="Public Property Network As String" />
      <MemberSignature Language="F#" Value="member this.Network : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable.Network" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="network")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9b4ec-110">取得またはネットワークの設定</span><span class="sxs-lookup"><span data-stu-id="9b4ec-110">Gets or sets network</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHop">
      <MemberSignature Language="C#" Value="public string NextHop { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextHop" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable.NextHop" />
      <MemberSignature Language="VB.NET" Value="Public Property NextHop As String" />
      <MemberSignature Language="F#" Value="member this.NextHop : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable.NextHop" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextHop")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9b4ec-111">取得または次ホップの設定</span><span class="sxs-lookup"><span data-stu-id="9b4ec-111">Gets or sets nextHop</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9b4ec-112">取得または設定のパス</span><span class="sxs-lookup"><span data-stu-id="9b4ec-112">Gets or sets path</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Weight">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Weight { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Weight" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable.Weight" />
      <MemberSignature Language="VB.NET" Value="Public Property Weight As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Weight : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitRoutesTable.Weight" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="weight")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9b4ec-113">取得または重みを設定します。</span><span class="sxs-lookup"><span data-stu-id="9b4ec-113">Gets or sets weight.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>