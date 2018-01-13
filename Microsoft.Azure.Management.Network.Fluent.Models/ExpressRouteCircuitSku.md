<Type Name="ExpressRouteCircuitSku" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku">
  <TypeSignature Language="C#" Value="public class ExpressRouteCircuitSku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteCircuitSku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteCircuitSku" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitSku = class" />
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
            <span data-ttu-id="f3388-101">ExpressRouteCircuit に SKU が含まれています。</span><span class="sxs-lookup"><span data-stu-id="f3388-101">Contains SKU in an ExpressRouteCircuit.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f3388-102">ExpressRouteCircuitSku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f3388-102">Initializes a new instance of the ExpressRouteCircuitSku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitSku (string name = null, string tier = null, string family = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string tier, string family) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional tier As String = null, Optional family As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku : string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku (name, tier, family)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="tier" Type="System.String" />
        <Parameter Name="family" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="f3388-103">SKU の名前。</span><span class="sxs-lookup"><span data-stu-id="f3388-103">The name of the SKU.</span></span></param>
        <param name="tier"><span data-ttu-id="f3388-104">SKU の階層。</span><span class="sxs-lookup"><span data-stu-id="f3388-104">The tier of the SKU.</span></span> <span data-ttu-id="f3388-105">値は、'Standard' または 'Premium' です。</span><span class="sxs-lookup"><span data-stu-id="f3388-105">Possible values are 'Standard' and 'Premium'.</span></span> <span data-ttu-id="f3388-106">使用可能な値が含まれます: 'Standard'、'Premium'</span><span class="sxs-lookup"><span data-stu-id="f3388-106">Possible values include: 'Standard', 'Premium'</span></span></param>
        <param name="family"><span data-ttu-id="f3388-107">SKU ファミリ。</span><span class="sxs-lookup"><span data-stu-id="f3388-107">The family of the SKU.</span></span> <span data-ttu-id="f3388-108">使用可能な値が: 'UnlimitedData' および 'MeteredData' です。</span><span class="sxs-lookup"><span data-stu-id="f3388-108">Possible values are: 'UnlimitedData' and 'MeteredData'.</span></span> <span data-ttu-id="f3388-109">使用可能な値が含まれます: 'UnlimitedData'、'MeteredData'</span><span class="sxs-lookup"><span data-stu-id="f3388-109">Possible values include: 'UnlimitedData', 'MeteredData'</span></span></param>
        <summary>
            <span data-ttu-id="f3388-110">ExpressRouteCircuitSku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f3388-110">Initializes a new instance of the ExpressRouteCircuitSku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Family">
      <MemberSignature Language="C#" Value="public string Family { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Family" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku.Family" />
      <MemberSignature Language="VB.NET" Value="Public Property Family As String" />
      <MemberSignature Language="F#" Value="member this.Family : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku.Family" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="family")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3388-111">取得または SKU のファミリを設定します。</span><span class="sxs-lookup"><span data-stu-id="f3388-111">Gets or sets the family of the SKU.</span></span> <span data-ttu-id="f3388-112">使用可能な値が: 'UnlimitedData' および 'MeteredData' です。</span><span class="sxs-lookup"><span data-stu-id="f3388-112">Possible values are: 'UnlimitedData' and 'MeteredData'.</span></span> <span data-ttu-id="f3388-113">使用可能な値が含まれます: 'UnlimitedData'、'MeteredData'</span><span class="sxs-lookup"><span data-stu-id="f3388-113">Possible values include: 'UnlimitedData', 'MeteredData'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3388-114">取得または SKU の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="f3388-114">Gets or sets the name of the SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public string Tier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku.Tier" />
      <MemberSignature Language="VB.NET" Value="Public Property Tier As String" />
      <MemberSignature Language="F#" Value="member this.Tier : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3388-115">取得または SKU の層を設定します。</span><span class="sxs-lookup"><span data-stu-id="f3388-115">Gets or sets the tier of the SKU.</span></span> <span data-ttu-id="f3388-116">値は、'Standard' または 'Premium' です。</span><span class="sxs-lookup"><span data-stu-id="f3388-116">Possible values are 'Standard' and 'Premium'.</span></span> <span data-ttu-id="f3388-117">使用可能な値が含まれます: 'Standard'、'Premium'</span><span class="sxs-lookup"><span data-stu-id="f3388-117">Possible values include: 'Standard', 'Premium'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>