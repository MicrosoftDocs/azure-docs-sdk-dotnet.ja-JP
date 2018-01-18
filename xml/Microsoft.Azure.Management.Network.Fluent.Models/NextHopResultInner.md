<Type Name="NextHopResultInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner">
  <TypeSignature Language="C#" Value="public class NextHopResultInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NextHopResultInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner" />
  <TypeSignature Language="VB.NET" Value="Public Class NextHopResultInner" />
  <TypeSignature Language="F#" Value="type NextHopResultInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="73cec-101">指定した VM から次のホップ先に関する情報。</span><span class="sxs-lookup"><span data-stu-id="73cec-101">The information about next hop from the specified VM.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NextHopResultInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="73cec-102">NextHopResultInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="73cec-102">Initializes a new instance of the NextHopResultInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NextHopResultInner (string nextHopType = null, string nextHopIpAddress = null, string routeTableId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nextHopType, string nextHopIpAddress, string routeTableId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nextHopType As String = null, Optional nextHopIpAddress As String = null, Optional routeTableId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner : string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner (nextHopType, nextHopIpAddress, routeTableId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nextHopType" Type="System.String" />
        <Parameter Name="nextHopIpAddress" Type="System.String" />
        <Parameter Name="routeTableId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nextHopType"><span data-ttu-id="73cec-103">次ホップの種類。</span><span class="sxs-lookup"><span data-stu-id="73cec-103">Next hop type.</span></span> <span data-ttu-id="73cec-104">使用可能な値が含まれます: 'Internet'、'VirtualAppliance'、'VirtualNetworkGateway'、'VnetLocal'、'HyperNetGateway'、'None'</span><span class="sxs-lookup"><span data-stu-id="73cec-104">Possible values include: 'Internet', 'VirtualAppliance', 'VirtualNetworkGateway', 'VnetLocal', 'HyperNetGateway', 'None'</span></span></param>
        <param name="nextHopIpAddress"><span data-ttu-id="73cec-105">次ホップ IP アドレス</span><span class="sxs-lookup"><span data-stu-id="73cec-105">Next hop IP Address</span></span></param>
        <param name="routeTableId"><span data-ttu-id="73cec-106">返されるルートに関連付けられているルート テーブルのリソース識別子。</span><span class="sxs-lookup"><span data-stu-id="73cec-106">The resource identifier for the route table associated with the route being returned.</span></span> <span data-ttu-id="73cec-107">返されるルートがルートを作成したすべてのユーザーに対応していない場合、このフィールドは文字列になります、' システム ルート ' です。</span><span class="sxs-lookup"><span data-stu-id="73cec-107">If the route being returned does not correspond to any user created routes then this field will be the string 'System Route'.</span></span></param>
        <summary>
            <span data-ttu-id="73cec-108">NextHopResultInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="73cec-108">Initializes a new instance of the NextHopResultInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHopIpAddress">
      <MemberSignature Language="C#" Value="public string NextHopIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextHopIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner.NextHopIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property NextHopIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.NextHopIpAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner.NextHopIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextHopIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73cec-109">取得または次ホップ IP アドレスを設定</span><span class="sxs-lookup"><span data-stu-id="73cec-109">Gets or sets next hop IP Address</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHopType">
      <MemberSignature Language="C#" Value="public string NextHopType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextHopType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner.NextHopType" />
      <MemberSignature Language="VB.NET" Value="Public Property NextHopType As String" />
      <MemberSignature Language="F#" Value="member this.NextHopType : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner.NextHopType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextHopType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73cec-110">取得または次ホップの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="73cec-110">Gets or sets next hop type.</span></span> <span data-ttu-id="73cec-111">使用可能な値が含まれます: 'Internet'、'VirtualAppliance'、'VirtualNetworkGateway'、'VnetLocal'、'HyperNetGateway'、'None'</span><span class="sxs-lookup"><span data-stu-id="73cec-111">Possible values include: 'Internet', 'VirtualAppliance', 'VirtualNetworkGateway', 'VnetLocal', 'HyperNetGateway', 'None'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteTableId">
      <MemberSignature Language="C#" Value="public string RouteTableId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RouteTableId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner.RouteTableId" />
      <MemberSignature Language="VB.NET" Value="Public Property RouteTableId As String" />
      <MemberSignature Language="F#" Value="member this.RouteTableId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner.RouteTableId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="routeTableId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73cec-112">取得または返されるルートに関連付けられているルート テーブルのリソース識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="73cec-112">Gets or sets the resource identifier for the route table associated with the route being returned.</span></span> <span data-ttu-id="73cec-113">返されるルートがルートを作成したすべてのユーザーに対応していない場合、このフィールドは文字列になります、' システム ルート ' です。</span><span class="sxs-lookup"><span data-stu-id="73cec-113">If the route being returned does not correspond to any user created routes then this field will be the string 'System Route'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>