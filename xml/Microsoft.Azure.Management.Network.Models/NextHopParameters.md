<Type Name="NextHopParameters" FullName="Microsoft.Azure.Management.Network.Models.NextHopParameters">
  <TypeSignature Language="C#" Value="public class NextHopParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NextHopParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.NextHopParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class NextHopParameters" />
  <TypeSignature Language="F#" Value="type NextHopParameters = class" />
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
            <span data-ttu-id="f3c94-101">送信元と送信先のエンドポイントを定義するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f3c94-101">Parameters that define the source and destination endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NextHopParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NextHopParameters.#ctor" />
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
            <span data-ttu-id="f3c94-102">NextHopParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f3c94-102">Initializes a new instance of the NextHopParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NextHopParameters (string targetResourceId, string sourceIPAddress, string destinationIPAddress, string targetNicResourceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetResourceId, string sourceIPAddress, string destinationIPAddress, string targetNicResourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NextHopParameters.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetResourceId As String, sourceIPAddress As String, destinationIPAddress As String, Optional targetNicResourceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.NextHopParameters : string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.NextHopParameters" Usage="new Microsoft.Azure.Management.Network.Models.NextHopParameters (targetResourceId, sourceIPAddress, destinationIPAddress, targetNicResourceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="sourceIPAddress" Type="System.String" />
        <Parameter Name="destinationIPAddress" Type="System.String" />
        <Parameter Name="targetNicResourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetResourceId"><span data-ttu-id="f3c94-103">アクションの実行対象となるターゲット リソースのリソースの識別子です。</span><span class="sxs-lookup"><span data-stu-id="f3c94-103">The resource identifier of the target resource against which the action is to be performed.</span></span></param>
        <param name="sourceIPAddress"><span data-ttu-id="f3c94-104">発信元 IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="f3c94-104">The source IP address.</span></span></param>
        <param name="destinationIPAddress"><span data-ttu-id="f3c94-105">宛先 IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="f3c94-105">The destination IP address.</span></span></param>
        <param name="targetNicResourceId"><span data-ttu-id="f3c94-106">NIC の id。</span><span class="sxs-lookup"><span data-stu-id="f3c94-106">The NIC ID.</span></span> <span data-ttu-id="f3c94-107">(が複数の Nic の VM nic には、いずれかを IP 転送が有効になっている場合は、し、このパラメーター指定してください。</span><span class="sxs-lookup"><span data-stu-id="f3c94-107">(If VM has multiple NICs and IP forwarding is enabled on any of the nics, then this parameter must be specified.</span></span> <span data-ttu-id="f3c94-108">それ以外の場合省略可能)。</span><span class="sxs-lookup"><span data-stu-id="f3c94-108">Otherwise optional).</span></span></param>
        <summary>
            <span data-ttu-id="f3c94-109">NextHopParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f3c94-109">Initializes a new instance of the NextHopParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationIPAddress">
      <MemberSignature Language="C#" Value="public string DestinationIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DestinationIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NextHopParameters.DestinationIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.DestinationIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NextHopParameters.DestinationIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destinationIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3c94-110">取得または宛先 IP アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="f3c94-110">Gets or sets the destination IP address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceIPAddress">
      <MemberSignature Language="C#" Value="public string SourceIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NextHopParameters.SourceIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.SourceIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NextHopParameters.SourceIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3c94-111">取得または送信元 IP アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="f3c94-111">Gets or sets the source IP address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetNicResourceId">
      <MemberSignature Language="C#" Value="public string TargetNicResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetNicResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NextHopParameters.TargetNicResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetNicResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetNicResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NextHopParameters.TargetNicResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetNicResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3c94-112">取得または設定、NIC の id です。</span><span class="sxs-lookup"><span data-stu-id="f3c94-112">Gets or sets the NIC ID.</span></span> <span data-ttu-id="f3c94-113">(が複数の Nic の VM nic には、いずれかを IP 転送が有効になっている場合は、し、このパラメーター指定してください。</span><span class="sxs-lookup"><span data-stu-id="f3c94-113">(If VM has multiple NICs and IP forwarding is enabled on any of the nics, then this parameter must be specified.</span></span> <span data-ttu-id="f3c94-114">それ以外の場合省略可能)。</span><span class="sxs-lookup"><span data-stu-id="f3c94-114">Otherwise optional).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceId">
      <MemberSignature Language="C#" Value="public string TargetResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NextHopParameters.TargetResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NextHopParameters.TargetResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3c94-115">取得または設定は、アクションの実行対象となるターゲット リソースのリソース識別子。</span><span class="sxs-lookup"><span data-stu-id="f3c94-115">Gets or sets the resource identifier of the target resource against which the action is to be performed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NextHopParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="nextHopParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f3c94-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f3c94-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f3c94-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f3c94-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>