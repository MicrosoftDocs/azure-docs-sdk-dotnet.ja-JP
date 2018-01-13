<Type Name="AvailableProvidersListParameters" FullName="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters">
  <TypeSignature Language="C#" Value="public class AvailableProvidersListParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AvailableProvidersListParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class AvailableProvidersListParameters" />
  <TypeSignature Language="F#" Value="type AvailableProvidersListParameters = class" />
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
            使用可能なインターネット サービス プロバイダーの一覧を決定する制約。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProvidersListParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AvailableProvidersListParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProvidersListParameters (System.Collections.Generic.IList&lt;string&gt; azureLocations = null, string country = null, string state = null, string city = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; azureLocations, string country, string state, string city) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters.#ctor(System.Collections.Generic.IList{System.String},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional azureLocations As IList(Of String) = null, Optional country As String = null, Optional state As String = null, Optional city As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters : System.Collections.Generic.IList&lt;string&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" Usage="new Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters (azureLocations, country, state, city)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="azureLocations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="country" Type="System.String" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="city" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="azureLocations">Azure の地域の一覧。</param>
        <param name="country">使用可能なプロバイダーのリストの国。</param>
        <param name="state">使用可能なプロバイダーの一覧の状態です。</param>
        <param name="city">市区町村利用可能なプロバイダーの一覧についてはします。</param>
        <summary>
            AvailableProvidersListParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureLocations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AzureLocations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AzureLocations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters.AzureLocations" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureLocations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AzureLocations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters.AzureLocations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureLocations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure リージョンの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="City">
      <MemberSignature Language="C#" Value="public string City { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string City" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters.City" />
      <MemberSignature Language="VB.NET" Value="Public Property City As String" />
      <MemberSignature Language="F#" Value="member this.City : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters.City" />
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
            取得または使用可能なプロバイダーの一覧の市区町村を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Country">
      <MemberSignature Language="C#" Value="public string Country { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Country" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters.Country" />
      <MemberSignature Language="VB.NET" Value="Public Property Country As String" />
      <MemberSignature Language="F#" Value="member this.Country : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters.Country" />
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
            取得または使用可能なプロバイダーの一覧については、国を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters.State" />
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
            取得または使用可能なプロバイダーの一覧については、状態を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>