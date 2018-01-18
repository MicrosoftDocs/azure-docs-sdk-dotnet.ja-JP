<Type Name="VnetRouteInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner">
  <TypeSignature Language="C#" Value="public class VnetRouteInner : Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VnetRouteInner extends Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner" />
  <TypeSignature Language="VB.NET" Value="Public Class VnetRouteInner&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type VnetRouteInner = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ba97d-101">仮想ネットワーク ルート コントラクトが仮想ネットワークのルーティング情報を渡すために使用します。</span><span class="sxs-lookup"><span data-stu-id="ba97d-101">Virtual Network route contract used to pass routing information for a Virtual Network.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetRouteInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ba97d-102">VnetRouteInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ba97d-102">Initializes a new instance of the VnetRouteInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetRouteInner (string id = null, string name = null, string kind = null, string type = null, string vnetRouteName = null, string startAddress = null, string endAddress = null, string routeType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string vnetRouteName, string startAddress, string endAddress, string routeType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional vnetRouteName As String = null, Optional startAddress As String = null, Optional endAddress As String = null, Optional routeType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner (id, name, kind, type, vnetRouteName, startAddress, endAddress, routeType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="vnetRouteName" Type="System.String" />
        <Parameter Name="startAddress" Type="System.String" />
        <Parameter Name="endAddress" Type="System.String" />
        <Parameter Name="routeType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="kind">To be added.</param>
        <param name="type">To be added.</param>
        <param name="vnetRouteName">To be added.</param>
        <param name="startAddress">To be added.</param>
        <param name="endAddress">To be added.</param>
        <param name="routeType">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndAddress">
      <MemberSignature Language="C#" Value="public string EndAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.EndAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property EndAddress As String" />
      <MemberSignature Language="F#" Value="member this.EndAddress : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.EndAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba97d-103">取得またはこのルートの終了アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="ba97d-103">Gets or sets the ending address for this route.</span></span> <span data-ttu-id="ba97d-104">開始アドレスを CIDR 表記法で指定する場合、これを省略した必要があります。</span><span class="sxs-lookup"><span data-stu-id="ba97d-104">If the start address is specified in CIDR notation, this must be omitted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteType">
      <MemberSignature Language="C#" Value="public string RouteType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RouteType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.RouteType" />
      <MemberSignature Language="VB.NET" Value="Public Property RouteType As String" />
      <MemberSignature Language="F#" Value="member this.RouteType : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.RouteType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.routeType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="ba97d-105">これは、ルートの種類取得または設定します既定では、すべてのアプリ - 既定では RFC1918 の継承によって指定されたローカル アドレスの範囲へのルート - ルートが、実際の仮想ネットワーク ルート静的 - 静的ルートのアプリのみに設定から継承。</span><span class="sxs-lookup"><span data-stu-id="ba97d-105">Gets or sets the type of route this is: DEFAULT - By default, every app has routes to the local address ranges specified by RFC1918 INHERITED - Routes inherited from the real Virtual Network routes STATIC - Static route set on the app only</span></span>
             
             <span data-ttu-id="ba97d-106">これらの値は、仮想ネットワークと、アプリのルートを同期するため使用されます。</span><span class="sxs-lookup"><span data-stu-id="ba97d-106">These values will be used for syncing an app's routes with those from a Virtual Network.</span></span> <span data-ttu-id="ba97d-107">使用可能な値が含まれます: 'DEFAULT'、'継承された'、'STATIC'</span><span class="sxs-lookup"><span data-stu-id="ba97d-107">Possible values include: 'DEFAULT', 'INHERITED', 'STATIC'</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAddress">
      <MemberSignature Language="C#" Value="public string StartAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.StartAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property StartAddress As String" />
      <MemberSignature Language="F#" Value="member this.StartAddress : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.StartAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba97d-108">取得またはこのルートの開始アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="ba97d-108">Gets or sets the starting address for this route.</span></span> <span data-ttu-id="ba97d-109">場合、終了アドレスを指定できません CIDR 表記法これも含めることがあります。</span><span class="sxs-lookup"><span data-stu-id="ba97d-109">This may also include a CIDR notation, in which case the end address must not be specified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetRouteName">
      <MemberSignature Language="C#" Value="public string VnetRouteName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetRouteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.VnetRouteName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetRouteName As String" />
      <MemberSignature Language="F#" Value="member this.VnetRouteName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.VnetRouteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba97d-110">取得またはこのルートの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba97d-110">Gets or sets the name of this route.</span></span> <span data-ttu-id="ba97d-111">これは、サーバーによって返されるだけと、クライアントで設定する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="ba97d-111">This is only returned by the server and does not need to be set by the client.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>