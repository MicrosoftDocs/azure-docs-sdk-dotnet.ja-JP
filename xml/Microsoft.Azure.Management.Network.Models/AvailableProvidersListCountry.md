<Type Name="AvailableProvidersListCountry" FullName="Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry">
  <TypeSignature Language="C#" Value="public class AvailableProvidersListCountry" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AvailableProvidersListCountry extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry" />
  <TypeSignature Language="VB.NET" Value="Public Class AvailableProvidersListCountry" />
  <TypeSignature Language="F#" Value="type AvailableProvidersListCountry = class" />
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
            <span data-ttu-id="bcb37-101">国の詳細。</span><span class="sxs-lookup"><span data-stu-id="bcb37-101">Country details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProvidersListCountry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bcb37-102">AvailableProvidersListCountry クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bcb37-102">Initializes a new instance of the AvailableProvidersListCountry class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProvidersListCountry (string countryName = null, System.Collections.Generic.IList&lt;string&gt; providers = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListState&gt; states = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string countryName, class System.Collections.Generic.IList`1&lt;string&gt; providers, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.AvailableProvidersListState&gt; states) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.AvailableProvidersListState})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional countryName As String = null, Optional providers As IList(Of String) = null, Optional states As IList(Of AvailableProvidersListState) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry : string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListState&gt; -&gt; Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry" Usage="new Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry (countryName, providers, states)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="countryName" Type="System.String" />
        <Parameter Name="providers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="states" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListState&gt;" />
      </Parameters>
      <Docs>
        <param name="countryName"><span data-ttu-id="bcb37-103">国または地域名。</span><span class="sxs-lookup"><span data-stu-id="bcb37-103">The country name.</span></span></param>
        <param name="providers"><span data-ttu-id="bcb37-104">インターネット サービス プロバイダーの一覧。</span><span class="sxs-lookup"><span data-stu-id="bcb37-104">A list of Internet service providers.</span></span></param>
        <param name="states"><span data-ttu-id="bcb37-105">国で使用可能な状態の一覧です。</span><span class="sxs-lookup"><span data-stu-id="bcb37-105">List of available states in the country.</span></span></param>
        <summary>
            <span data-ttu-id="bcb37-106">AvailableProvidersListCountry クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bcb37-106">Initializes a new instance of the AvailableProvidersListCountry class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CountryName">
      <MemberSignature Language="C#" Value="public string CountryName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CountryName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry.CountryName" />
      <MemberSignature Language="VB.NET" Value="Public Property CountryName As String" />
      <MemberSignature Language="F#" Value="member this.CountryName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry.CountryName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="countryName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bcb37-107">取得または国または地域名を設定します。</span><span class="sxs-lookup"><span data-stu-id="bcb37-107">Gets or sets the country name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Providers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Providers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Providers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry.Providers" />
      <MemberSignature Language="VB.NET" Value="Public Property Providers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Providers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry.Providers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="providers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bcb37-108">取得またはインターネット サービス プロバイダーの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="bcb37-108">Gets or sets a list of Internet service providers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="States">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListState&gt; States { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.AvailableProvidersListState&gt; States" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry.States" />
      <MemberSignature Language="VB.NET" Value="Public Property States As IList(Of AvailableProvidersListState)" />
      <MemberSignature Language="F#" Value="member this.States : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListState&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry.States" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="states")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bcb37-109">取得または国で使用可能な状態の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="bcb37-109">Gets or sets list of available states in the country.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>