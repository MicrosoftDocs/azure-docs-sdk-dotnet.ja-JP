<Type Name="CustomDomainInner" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner">
  <TypeSignature Language="C#" Value="public class CustomDomainInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CustomDomainInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner" />
  <TypeSignature Language="VB.NET" Value="Public Class CustomDomainInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type CustomDomainInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
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
            顧客には、商標、www.consoto.com などのドメインが用意されています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomDomainInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CustomDomainInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomDomainInner (string hostName, string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string resourceState = null, string customHttpsProvisioningState = null, string validationData = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string resourceState, string customHttpsProvisioningState, string validationData, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional resourceState As String = null, Optional customHttpsProvisioningState As String = null, Optional validationData As String = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner : string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner (hostName, location, id, name, type, tags, resourceState, customHttpsProvisioningState, validationData, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="resourceState" Type="System.String" />
        <Parameter Name="customHttpsProvisioningState" Type="System.String" />
        <Parameter Name="validationData" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName">カスタム ドメインのホスト名。 ドメイン名である必要があります。</param>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="resourceState">カスタム ドメインのリソースの状態。
            使用可能な値が含まれます: '作成中'、'Active'、'削除'</param>
        <param name="customHttpsProvisioningState">カスタム ドメインのカスタムの Https のプロビジョニング状態。 使用可能な値が含まれます: 'を有効にする'、'Enabled'、'を無効にする'、'Disabled'、'失敗'</param>
        <param name="validationData">ローカルのコンプライアンス上の理由により、一部の地域に CDN を配信する場合、特別な検証またはデータが必要な可能性があります。 例:  中国でのコンテンツを配信するには、カスタム ドメインの ICP ライセンスの数が必要です。</param>
        <param name="provisioningState">カスタム ドメインの状態を準備しています。</param>
        <summary>
            CustomDomainInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomHttpsProvisioningState">
      <MemberSignature Language="C#" Value="public string CustomHttpsProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomHttpsProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.CustomHttpsProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomHttpsProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.CustomHttpsProvisioningState : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.CustomHttpsProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customHttpsProvisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            カスタム ドメインのカスタムの Https の状態をプロビジョニングを取得します。
            使用可能な値が含まれます: 'を有効にする'、'Enabled'、'を無効にする'、'Disabled'、'失敗'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.HostName" />
      <MemberSignature Language="VB.NET" Value="Public Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはカスタムのドメインのホスト名を設定します。 ドメイン名である必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
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
            カスタム ドメインの状態のプロビジョニングを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceState">
      <MemberSignature Language="C#" Value="public string ResourceState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.ResourceState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceState As String" />
      <MemberSignature Language="F#" Value="member this.ResourceState : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.ResourceState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            カスタム ドメインのリソースの状態を取得します。 使用可能な値が含まれます: '作成中'、'Active'、'削除'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="customDomainInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ValidationData">
      <MemberSignature Language="C#" Value="public string ValidationData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ValidationData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.ValidationData" />
      <MemberSignature Language="VB.NET" Value="Public Property ValidationData As String" />
      <MemberSignature Language="F#" Value="member this.ValidationData : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.ValidationData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.validationData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ローカルのコンプライアンス上の理由により、一部の地域に CDN を配信するときに、取得または設定の特別な検証またはデータを必要なことがあります。
            例:  中国でのコンテンツを配信するには、カスタム ドメインの ICP ライセンスの数が必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>