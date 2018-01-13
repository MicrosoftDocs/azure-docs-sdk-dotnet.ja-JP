<Type Name="AzureReachabilityReportLocation" FullName="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation">
  <TypeSignature Language="C#" Value="public class AzureReachabilityReportLocation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureReachabilityReportLocation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureReachabilityReportLocation" />
  <TypeSignature Language="F#" Value="type AzureReachabilityReportLocation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8ce81-101">地理的な場所を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="8ce81-101">Parameters that define a geographic location.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureReachabilityReportLocation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8ce81-102">AzureReachabilityReportLocation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8ce81-102">Initializes a new instance of the AzureReachabilityReportLocation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureReachabilityReportLocation (string country, string state = null, string city = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string country, string state, string city) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (country As String, Optional state As String = null, Optional city As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation : string * string * string -&gt; Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation" Usage="new Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation (country, state, city)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="country" Type="System.String" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="city" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="country"><span data-ttu-id="8ce81-103">国の名前。</span><span class="sxs-lookup"><span data-stu-id="8ce81-103">The name of the country.</span></span></param>
        <param name="state"><span data-ttu-id="8ce81-104">状態の名前。</span><span class="sxs-lookup"><span data-stu-id="8ce81-104">The name of the state.</span></span></param>
        <param name="city"><span data-ttu-id="8ce81-105">市区町村の名前。</span><span class="sxs-lookup"><span data-stu-id="8ce81-105">The name of the city or town.</span></span></param>
        <summary>
            <span data-ttu-id="8ce81-106">AzureReachabilityReportLocation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8ce81-106">Initializes a new instance of the AzureReachabilityReportLocation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="City">
      <MemberSignature Language="C#" Value="public string City { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string City" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation.City" />
      <MemberSignature Language="VB.NET" Value="Public Property City As String" />
      <MemberSignature Language="F#" Value="member this.City : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation.City" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="city")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ce81-107">取得または市区町村の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ce81-107">Gets or sets the name of the city or town.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Country">
      <MemberSignature Language="C#" Value="public string Country { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Country" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation.Country" />
      <MemberSignature Language="VB.NET" Value="Public Property Country As String" />
      <MemberSignature Language="F#" Value="member this.Country : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation.Country" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="country")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ce81-108">取得または国の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ce81-108">Gets or sets the name of the country.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ce81-109">取得または設定の状態の名前。</span><span class="sxs-lookup"><span data-stu-id="8ce81-109">Gets or sets the name of the state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="azureReachabilityReportLocation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8ce81-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="8ce81-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8ce81-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8ce81-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>