<Type Name="ApplicationGatewayInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="611ff-101">アプリケーション ゲートウェイ リソース</span><span class="sxs-lookup"><span data-stu-id="611ff-101">Application gateway resource</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="611ff-102">ApplicationGatewayInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="611ff-102">Initializes a new instance of the ApplicationGatewayInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySku sku = null, Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy sslPolicy = null, string operationalState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayIPConfigurationInner&gt; gatewayIPConfigurations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAuthenticationCertificateInner&gt; authenticationCertificates = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslCertificateInner&gt; sslCertificates = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendIPConfigurationInner&gt; frontendIPConfigurations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendPortInner&gt; frontendPorts = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProbeInner&gt; probes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner&gt; backendAddressPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner&gt; backendHttpSettingsCollection = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayHttpListenerInner&gt; httpListeners = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayUrlPathMapInner&gt; urlPathMaps = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRequestRoutingRuleInner&gt; requestRoutingRules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRedirectConfigurationInner&gt; redirectConfigurations = null, Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayWebApplicationFirewallConfiguration webApplicationFirewallConfiguration = null, string resourceGuid = null, string provisioningState = null, string etag = null, System.Collections.Generic.IList&lt;string&gt; zones = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySku sku, class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy sslPolicy, string operationalState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayIPConfigurationInner&gt; gatewayIPConfigurations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAuthenticationCertificateInner&gt; authenticationCertificates, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslCertificateInner&gt; sslCertificates, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendIPConfigurationInner&gt; frontendIPConfigurations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendPortInner&gt; frontendPorts, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProbeInner&gt; probes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner&gt; backendAddressPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner&gt; backendHttpSettingsCollection, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayHttpListenerInner&gt; httpListeners, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayUrlPathMapInner&gt; urlPathMaps, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRequestRoutingRuleInner&gt; requestRoutingRules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRedirectConfigurationInner&gt; redirectConfigurations, class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayWebApplicationFirewallConfiguration webApplicationFirewallConfiguration, string resourceGuid, string provisioningState, string etag, class System.Collections.Generic.IList`1&lt;string&gt; zones) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySku,Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayIPConfigurationInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAuthenticationCertificateInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslCertificateInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendIPConfigurationInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendPortInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProbeInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayHttpListenerInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayUrlPathMapInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRequestRoutingRuleInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRedirectConfigurationInner},Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayWebApplicationFirewallConfiguration,System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional sku As ApplicationGatewaySku = null, Optional sslPolicy As ApplicationGatewaySslPolicy = null, Optional operationalState As String = null, Optional gatewayIPConfigurations As IList(Of ApplicationGatewayIPConfigurationInner) = null, Optional authenticationCertificates As IList(Of ApplicationGatewayAuthenticationCertificateInner) = null, Optional sslCertificates As IList(Of ApplicationGatewaySslCertificateInner) = null, Optional frontendIPConfigurations As IList(Of ApplicationGatewayFrontendIPConfigurationInner) = null, Optional frontendPorts As IList(Of ApplicationGatewayFrontendPortInner) = null, Optional probes As IList(Of ApplicationGatewayProbeInner) = null, Optional backendAddressPools As IList(Of ApplicationGatewayBackendAddressPoolInner) = null, Optional backendHttpSettingsCollection As IList(Of ApplicationGatewayBackendHttpSettingsInner) = null, Optional httpListeners As IList(Of ApplicationGatewayHttpListenerInner) = null, Optional urlPathMaps As IList(Of ApplicationGatewayUrlPathMapInner) = null, Optional requestRoutingRules As IList(Of ApplicationGatewayRequestRoutingRuleInner) = null, Optional redirectConfigurations As IList(Of ApplicationGatewayRedirectConfigurationInner) = null, Optional webApplicationFirewallConfiguration As ApplicationGatewayWebApplicationFirewallConfiguration = null, Optional resourceGuid As String = null, Optional provisioningState As String = null, Optional etag As String = null, Optional zones As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySku * Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayIPConfigurationInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAuthenticationCertificateInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslCertificateInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendIPConfigurationInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendPortInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProbeInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayHttpListenerInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayUrlPathMapInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRequestRoutingRuleInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRedirectConfigurationInner&gt; * Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayWebApplicationFirewallConfiguration * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner (location, id, name, type, tags, sku, sslPolicy, operationalState, gatewayIPConfigurations, authenticationCertificates, sslCertificates, frontendIPConfigurations, frontendPorts, probes, backendAddressPools, backendHttpSettingsCollection, httpListeners, urlPathMaps, requestRoutingRules, redirectConfigurations, webApplicationFirewallConfiguration, resourceGuid, provisioningState, etag, zones)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySku" />
        <Parameter Name="sslPolicy" Type="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy" />
        <Parameter Name="operationalState" Type="System.String" />
        <Parameter Name="gatewayIPConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayIPConfigurationInner&gt;" />
        <Parameter Name="authenticationCertificates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAuthenticationCertificateInner&gt;" />
        <Parameter Name="sslCertificates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslCertificateInner&gt;" />
        <Parameter Name="frontendIPConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendIPConfigurationInner&gt;" />
        <Parameter Name="frontendPorts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendPortInner&gt;" />
        <Parameter Name="probes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProbeInner&gt;" />
        <Parameter Name="backendAddressPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner&gt;" />
        <Parameter Name="backendHttpSettingsCollection" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner&gt;" />
        <Parameter Name="httpListeners" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayHttpListenerInner&gt;" />
        <Parameter Name="urlPathMaps" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayUrlPathMapInner&gt;" />
        <Parameter Name="requestRoutingRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRequestRoutingRuleInner&gt;" />
        <Parameter Name="redirectConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRedirectConfigurationInner&gt;" />
        <Parameter Name="webApplicationFirewallConfiguration" Type="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayWebApplicationFirewallConfiguration" />
        <Parameter Name="resourceGuid" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="zones" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="sku">To be added.</param>
        <param name="sslPolicy">To be added.</param>
        <param name="operationalState">To be added.</param>
        <param name="gatewayIPConfigurations">To be added.</param>
        <param name="authenticationCertificates">To be added.</param>
        <param name="sslCertificates">To be added.</param>
        <param name="frontendIPConfigurations">To be added.</param>
        <param name="frontendPorts">To be added.</param>
        <param name="probes">To be added.</param>
        <param name="backendAddressPools">To be added.</param>
        <param name="backendHttpSettingsCollection">To be added.</param>
        <param name="httpListeners">To be added.</param>
        <param name="urlPathMaps">To be added.</param>
        <param name="requestRoutingRules">To be added.</param>
        <param name="redirectConfigurations">To be added.</param>
        <param name="webApplicationFirewallConfiguration">To be added.</param>
        <param name="resourceGuid">To be added.</param>
        <param name="provisioningState">To be added.</param>
        <param name="etag">To be added.</param>
        <param name="zones">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationCertificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAuthenticationCertificateInner&gt; AuthenticationCertificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAuthenticationCertificateInner&gt; AuthenticationCertificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.AuthenticationCertificates" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationCertificates As IList(Of ApplicationGatewayAuthenticationCertificateInner)" />
      <MemberSignature Language="F#" Value="member this.AuthenticationCertificates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAuthenticationCertificateInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.AuthenticationCertificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authenticationCertificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAuthenticationCertificateInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-103">取得またはアプリケーション ゲートウェイ リソースの認証証明書を設定します。</span><span class="sxs-lookup"><span data-stu-id="611ff-103">Gets or sets authentication certificates of the application gateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendAddressPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner&gt; BackendAddressPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner&gt; BackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.BackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendAddressPools As IList(Of ApplicationGatewayBackendAddressPoolInner)" />
      <MemberSignature Language="F#" Value="member this.BackendAddressPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.BackendAddressPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendAddressPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-104">取得またはアプリケーション ゲートウェイ リソースのバックエンド アドレス プールを設定します。</span><span class="sxs-lookup"><span data-stu-id="611ff-104">Gets or sets backend address pool of the application gateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendHttpSettingsCollection">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner&gt; BackendHttpSettingsCollection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner&gt; BackendHttpSettingsCollection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.BackendHttpSettingsCollection" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendHttpSettingsCollection As IList(Of ApplicationGatewayBackendHttpSettingsInner)" />
      <MemberSignature Language="F#" Value="member this.BackendHttpSettingsCollection : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.BackendHttpSettingsCollection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendHttpSettingsCollection")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-105">取得またはバックエンド アプリケーション ゲートウェイ リソースの http 設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="611ff-105">Gets or sets backend http settings of the application gateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-106">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="611ff-106">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendIPConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendIPConfigurationInner&gt; FrontendIPConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendIPConfigurationInner&gt; FrontendIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.FrontendIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendIPConfigurations As IList(Of ApplicationGatewayFrontendIPConfigurationInner)" />
      <MemberSignature Language="F#" Value="member this.FrontendIPConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendIPConfigurationInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.FrontendIPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendIPConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendIPConfigurationInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-107">取得またはフロント エンド アプリケーション ゲートウェイ リソースの IP アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="611ff-107">Gets or sets frontend IP addresses of the application gateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPorts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendPortInner&gt; FrontendPorts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendPortInner&gt; FrontendPorts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.FrontendPorts" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPorts As IList(Of ApplicationGatewayFrontendPortInner)" />
      <MemberSignature Language="F#" Value="member this.FrontendPorts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendPortInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.FrontendPorts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendPorts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendPortInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-108">取得またはフロント エンド アプリケーション ゲートウェイ リソースのポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="611ff-108">Gets or sets frontend ports of the application gateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayIPConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayIPConfigurationInner&gt; GatewayIPConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayIPConfigurationInner&gt; GatewayIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.GatewayIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayIPConfigurations As IList(Of ApplicationGatewayIPConfigurationInner)" />
      <MemberSignature Language="F#" Value="member this.GatewayIPConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayIPConfigurationInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.GatewayIPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gatewayIPConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayIPConfigurationInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-109">取得または、ゲートウェイ リソースをアプリケーションのサブネットに設定します。</span><span class="sxs-lookup"><span data-stu-id="611ff-109">Gets or sets subnets of application the gateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpListeners">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayHttpListenerInner&gt; HttpListeners { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayHttpListenerInner&gt; HttpListeners" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.HttpListeners" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpListeners As IList(Of ApplicationGatewayHttpListenerInner)" />
      <MemberSignature Language="F#" Value="member this.HttpListeners : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayHttpListenerInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.HttpListeners" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.httpListeners")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayHttpListenerInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-110">取得またはアプリケーション ゲートウェイ リソースの http リスナーを設定します。</span><span class="sxs-lookup"><span data-stu-id="611ff-110">Gets or sets http listeners of the application gateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationalState">
      <MemberSignature Language="C#" Value="public string OperationalState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationalState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.OperationalState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationalState As String" />
      <MemberSignature Language="F#" Value="member this.OperationalState : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.OperationalState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operationalState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-111">アプリケーション ゲートウェイ リソースの操作状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="611ff-111">Gets operational state of the application gateway resource.</span></span>
            <span data-ttu-id="611ff-112">使用可能な値が: '停止'、'開始'、'実行中'、'停止' です。</span><span class="sxs-lookup"><span data-stu-id="611ff-112">Possible values are: 'Stopped', 'Started', 'Running', and 'Stopping'.</span></span> <span data-ttu-id="611ff-113">使用可能な値が含まれます: '停止'、'開始'、'実行中'、'停止'</span><span class="sxs-lookup"><span data-stu-id="611ff-113">Possible values include: 'Stopped', 'Starting', 'Running', 'Stopping'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Probes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProbeInner&gt; Probes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProbeInner&gt; Probes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.Probes" />
      <MemberSignature Language="VB.NET" Value="Public Property Probes As IList(Of ApplicationGatewayProbeInner)" />
      <MemberSignature Language="F#" Value="member this.Probes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProbeInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.Probes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.probes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProbeInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-114">取得またはアプリケーション ゲートウェイ リソースのプローブを設定します。</span><span class="sxs-lookup"><span data-stu-id="611ff-114">Gets or sets probes of the application gateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-115">取得またはアプリケーション ゲートウェイ リソースのプロビジョニング状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="611ff-115">Gets or sets provisioning state of the application gateway resource.</span></span> <span data-ttu-id="611ff-116">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="611ff-116">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedirectConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRedirectConfigurationInner&gt; RedirectConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRedirectConfigurationInner&gt; RedirectConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.RedirectConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property RedirectConfigurations As IList(Of ApplicationGatewayRedirectConfigurationInner)" />
      <MemberSignature Language="F#" Value="member this.RedirectConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRedirectConfigurationInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.RedirectConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.redirectConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRedirectConfigurationInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestRoutingRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRequestRoutingRuleInner&gt; RequestRoutingRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRequestRoutingRuleInner&gt; RequestRoutingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.RequestRoutingRules" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestRoutingRules As IList(Of ApplicationGatewayRequestRoutingRuleInner)" />
      <MemberSignature Language="F#" Value="member this.RequestRoutingRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRequestRoutingRuleInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.RequestRoutingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestRoutingRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayRequestRoutingRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-117">取得またはアプリケーション ゲートウェイ リソースの要求のルーティング規則を設定します。</span><span class="sxs-lookup"><span data-stu-id="611ff-117">Gets or sets request routing rules of the application gateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.ResourceGuid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceGuid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-118">取得またはリソース GUID、アプリケーション ゲートウェイのリソースのプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="611ff-118">Gets or sets resource GUID property of the application gateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As ApplicationGatewaySku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySku with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-119">取得またはアプリケーション ゲートウェイ リソースの SKU を設定します。</span><span class="sxs-lookup"><span data-stu-id="611ff-119">Gets or sets SKU of the application gateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SslCertificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslCertificateInner&gt; SslCertificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslCertificateInner&gt; SslCertificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.SslCertificates" />
      <MemberSignature Language="VB.NET" Value="Public Property SslCertificates As IList(Of ApplicationGatewaySslCertificateInner)" />
      <MemberSignature Language="F#" Value="member this.SslCertificates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslCertificateInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.SslCertificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sslCertificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslCertificateInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-120">取得またはアプリケーション ゲートウェイ リソースの SSL 証明書を設定します。</span><span class="sxs-lookup"><span data-stu-id="611ff-120">Gets or sets SSL certificates of the application gateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SslPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy SslPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy SslPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.SslPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property SslPolicy As ApplicationGatewaySslPolicy" />
      <MemberSignature Language="F#" Value="member this.SslPolicy : Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.SslPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sslPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-121">取得またはアプリケーション ゲートウェイ リソースの SSL ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="611ff-121">Gets or sets SSL policy of the application gateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UrlPathMaps">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayUrlPathMapInner&gt; UrlPathMaps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayUrlPathMapInner&gt; UrlPathMaps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.UrlPathMaps" />
      <MemberSignature Language="VB.NET" Value="Public Property UrlPathMaps As IList(Of ApplicationGatewayUrlPathMapInner)" />
      <MemberSignature Language="F#" Value="member this.UrlPathMaps : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayUrlPathMapInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.UrlPathMaps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.urlPathMaps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayUrlPathMapInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-122">取得またはアプリケーション ゲートウェイ リソースの URL パスのマップを設定します。</span><span class="sxs-lookup"><span data-stu-id="611ff-122">Gets or sets URL path map of the application gateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="applicationGatewayInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="611ff-123">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="611ff-123">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="611ff-124">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="611ff-124">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WebApplicationFirewallConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayWebApplicationFirewallConfiguration WebApplicationFirewallConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayWebApplicationFirewallConfiguration WebApplicationFirewallConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.WebApplicationFirewallConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property WebApplicationFirewallConfiguration As ApplicationGatewayWebApplicationFirewallConfiguration" />
      <MemberSignature Language="F#" Value="member this.WebApplicationFirewallConfiguration : Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayWebApplicationFirewallConfiguration with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.WebApplicationFirewallConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.webApplicationFirewallConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayWebApplicationFirewallConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="611ff-125">取得または web アプリケーション ファイアウォール構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="611ff-125">Gets or sets web application firewall configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Zones">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Zones { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Zones" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.Zones" />
      <MemberSignature Language="VB.NET" Value="Public Property Zones As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Zones : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner.Zones" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="zones")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>