<Type Name="ServiceEndpointPropertiesFormat" FullName="Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat">
  <TypeSignature Language="C#" Value="public class ServiceEndpointPropertiesFormat" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceEndpointPropertiesFormat extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceEndpointPropertiesFormat" />
  <TypeSignature Language="F#" Value="type ServiceEndpointPropertiesFormat = class" />
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
            <span data-ttu-id="fae0f-101">サービス エンドポイントのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="fae0f-101">The service endpoint properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceEndpointPropertiesFormat ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat.#ctor" />
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
            <span data-ttu-id="fae0f-102">ServiceEndpointPropertiesFormat クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fae0f-102">Initializes a new instance of the ServiceEndpointPropertiesFormat class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceEndpointPropertiesFormat (string service = null, System.Collections.Generic.IList&lt;string&gt; locations = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string service, class System.Collections.Generic.IList`1&lt;string&gt; locations, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat.#ctor(System.String,System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional service As String = null, Optional locations As IList(Of String) = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat : string * System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat" Usage="new Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat (service, locations, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="service" Type="System.String" />
        <Parameter Name="locations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="service"><span data-ttu-id="fae0f-103">エンドポイント サービスの型。</span><span class="sxs-lookup"><span data-stu-id="fae0f-103">The type of the endpoint service.</span></span></param>
        <param name="locations"><span data-ttu-id="fae0f-104">場所の一覧。</span><span class="sxs-lookup"><span data-stu-id="fae0f-104">A list of locations.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="fae0f-105">リソースのプロビジョニングの状態。</span><span class="sxs-lookup"><span data-stu-id="fae0f-105">The provisioning state of the resource.</span></span></param>
        <summary>
            <span data-ttu-id="fae0f-106">ServiceEndpointPropertiesFormat クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fae0f-106">Initializes a new instance of the ServiceEndpointPropertiesFormat class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Locations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Locations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Locations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat.Locations" />
      <MemberSignature Language="VB.NET" Value="Public Property Locations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Locations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat.Locations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="locations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fae0f-107">取得または場所の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="fae0f-107">Gets or sets a list of locations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fae0f-108">取得またはリソースのプロビジョニングの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="fae0f-108">Gets or sets the provisioning state of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Service">
      <MemberSignature Language="C#" Value="public string Service { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Service" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat.Service" />
      <MemberSignature Language="VB.NET" Value="Public Property Service As String" />
      <MemberSignature Language="F#" Value="member this.Service : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat.Service" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="service")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fae0f-109">取得またはエンドポイント サービスの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="fae0f-109">Gets or sets the type of the endpoint service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>