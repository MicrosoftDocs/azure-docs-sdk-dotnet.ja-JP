<Type Name="ApplicationGatewayAvailableSslOptions" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayAvailableSslOptions : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayAvailableSslOptions extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayAvailableSslOptions&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayAvailableSslOptions = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            ApplicationGatewayAvailableSslOptions API サービスの呼び出しの応答です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayAvailableSslOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions.#ctor" />
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
            ApplicationGatewayAvailableSslOptions クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayAvailableSslOptions (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; predefinedPolicies = null, string defaultPolicy = null, System.Collections.Generic.IList&lt;string&gt; availableCipherSuites = null, System.Collections.Generic.IList&lt;string&gt; availableProtocols = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; predefinedPolicies, string defaultPolicy, class System.Collections.Generic.IList`1&lt;string&gt; availableCipherSuites, class System.Collections.Generic.IList`1&lt;string&gt; availableProtocols) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.SubResource},System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional predefinedPolicies As IList(Of SubResource) = null, Optional defaultPolicy As String = null, Optional availableCipherSuites As IList(Of String) = null, Optional availableProtocols As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions (id, name, type, location, tags, predefinedPolicies, defaultPolicy, availableCipherSuites, availableProtocols)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="predefinedPolicies" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;" />
        <Parameter Name="defaultPolicy" Type="System.String" />
        <Parameter Name="availableCipherSuites" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="availableProtocols" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id">リソースの ID</param>
        <param name="name">リソース名。</param>
        <param name="type">リソースの種類。</param>
        <param name="location">リソースの場所。</param>
        <param name="tags">リソース タグ。</param>
        <param name="predefinedPolicies">使用可能な Ssl の一覧には、ポリシーが定義されています。</param>
        <param name="defaultPolicy">Ssl の名前には、アプリケーション ゲートウェイに既定で適用されるポリシーが定義されています。 使用可能な値が含まれます: 'AppGwSslPolicy20150501'、'AppGwSslPolicy20170401'、'AppGwSslPolicy20170401S'</param>
        <param name="availableCipherSuites">使用可能な Ssl 暗号スイートの一覧です。</param>
        <param name="availableProtocols">利用可能な Ssl プロトコルの一覧です。</param>
        <summary>
            ApplicationGatewayAvailableSslOptions クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableCipherSuites">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AvailableCipherSuites { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AvailableCipherSuites" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions.AvailableCipherSuites" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailableCipherSuites As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AvailableCipherSuites : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions.AvailableCipherSuites" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availableCipherSuites")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用可能な Ssl 暗号スイートの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableProtocols">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AvailableProtocols { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AvailableProtocols" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions.AvailableProtocols" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailableProtocols As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AvailableProtocols : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions.AvailableProtocols" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availableProtocols")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用可能な Ssl プロトコルの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultPolicy">
      <MemberSignature Language="C#" Value="public string DefaultPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions.DefaultPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultPolicy As String" />
      <MemberSignature Language="F#" Value="member this.DefaultPolicy : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions.DefaultPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーション ゲートウェイに既定で適用される定義済みの Ssl ポリシーの名前を設定します。 使用可能な値が含まれます: 'AppGwSslPolicy20150501'、'AppGwSslPolicy20170401'、'AppGwSslPolicy20170401S'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PredefinedPolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; PredefinedPolicies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; PredefinedPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions.PredefinedPolicies" />
      <MemberSignature Language="VB.NET" Value="Public Property PredefinedPolicies As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.PredefinedPolicies : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayAvailableSslOptions.PredefinedPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.predefinedPolicies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用可能な定義済みの Ssl ポリシーの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>