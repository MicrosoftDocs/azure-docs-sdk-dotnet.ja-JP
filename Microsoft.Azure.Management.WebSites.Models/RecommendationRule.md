<Type Name="RecommendationRule" FullName="Microsoft.Azure.Management.WebSites.Models.RecommendationRule">
  <TypeSignature Language="C#" Value="public class RecommendationRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecommendationRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.RecommendationRule" />
  <TypeSignature Language="VB.NET" Value="Public Class RecommendationRule" />
  <TypeSignature Language="F#" Value="type RecommendationRule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            リコメンデーション エンジンを実行できるリコメンデーション ルールを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendationRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            RecommendationRule クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendationRule (string name = null, string displayName = null, string message = null, Nullable&lt;Guid&gt; recommendationId = null, string description = null, string actionName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; level = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt; channels = null, System.Collections.Generic.IList&lt;string&gt; tags = null, Nullable&lt;bool&gt; isDynamic = null, string extensionName = null, string bladeName = null, string forwardLink = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string displayName, string message, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; recommendationId, string description, string actionName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; level, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.Channels&gt; channels, class System.Collections.Generic.IList`1&lt;string&gt; tags, valuetype System.Nullable`1&lt;bool&gt; isDynamic, string extensionName, string bladeName, string forwardLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.#ctor(System.String,System.String,System.String,System.Nullable{System.Guid},System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.NotificationLevel},System.Nullable{Microsoft.Azure.Management.WebSites.Models.Channels},System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional displayName As String = null, Optional message As String = null, Optional recommendationId As Nullable(Of Guid) = null, Optional description As String = null, Optional actionName As String = null, Optional level As Nullable(Of NotificationLevel) = null, Optional channels As Nullable(Of Channels) = null, Optional tags As IList(Of String) = null, Optional isDynamic As Nullable(Of Boolean) = null, Optional extensionName As String = null, Optional bladeName As String = null, Optional forwardLink As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.RecommendationRule : string * string * string * Nullable&lt;Guid&gt; * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.RecommendationRule" Usage="new Microsoft.Azure.Management.WebSites.Models.RecommendationRule (name, displayName, message, recommendationId, description, actionName, level, channels, tags, isDynamic, extensionName, bladeName, forwardLink)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="recommendationId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="actionName" Type="System.String" />
        <Parameter Name="level" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt;" />
        <Parameter Name="channels" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt;" />
        <Parameter Name="tags" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="isDynamic" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="extensionName" Type="System.String" />
        <Parameter Name="bladeName" Type="System.String" />
        <Parameter Name="forwardLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">規則の一意の名前。</param>
        <param name="displayName">規則の UI の表示名。</param>
        <param name="message">ルール (UI に適している) のローカライズされた名前。</param>
        <param name="recommendationId">推奨設定が関連付けられているオブジェクトの ID が、そのルールに関連付けられている場合の推奨設定が存在します。
            設定されているようなオブジェクトが存在しない場合に null です。</param>
        <param name="description">ルールの詳細な説明をローカライズします。</param>
        <param name="actionName">文字列でこの規則によって推奨されるアクションの名前。</param>
        <param name="level">このルールは、重大度を示すへの影響のレベルです。 使用可能な値が含まれます: '重大'、'警告'、'情報'、'NonUrgentSuggestion'</param>
        <param name="channels">このルールが適用される利用可能なチャネルのリストです。 使用可能な値が含まれます: '通知'、'Api'、'電子メール'、'Webhook'、'All'</param>
        <param name="tags">ルールを含むカテゴリのタグの配列。</param>
        <param name="isDynamic">これは、動的に追加された規則に関連付ける場合は true。</param>
        <param name="extensionName">場合は、ポータルの拡張機能の名前が存在します。
            ダイナミック ルールのみに適用されます。</param>
        <param name="bladeName">ポータルのブレードへのディープ リンクします。
            ダイナミック ルールのみに適用されます。</param>
        <param name="forwardLink">ルールに関連付けられている外部ドキュメントへのリンクを転送します。 ダイナミック ルールのみに適用されます。</param>
        <summary>
            RecommendationRule クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionName">
      <MemberSignature Language="C#" Value="public string ActionName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ActionName" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionName As String" />
      <MemberSignature Language="F#" Value="member this.ActionName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ActionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actionName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または文字列でこの規則によって推奨されるアクションの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BladeName">
      <MemberSignature Language="C#" Value="public string BladeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BladeName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.BladeName" />
      <MemberSignature Language="VB.NET" Value="Public Property BladeName As String" />
      <MemberSignature Language="F#" Value="member this.BladeName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.BladeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bladeName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはポータルのブレードをディープ リンクを設定します。 ダイナミック ルールのみに適用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Channels">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt; Channels { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.Channels&gt; Channels" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Channels" />
      <MemberSignature Language="VB.NET" Value="Public Property Channels As Nullable(Of Channels)" />
      <MemberSignature Language="F#" Value="member this.Channels : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Channels" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="channels")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この規則が適用される利用可能なチャネルのリストを設定します。
            使用可能な値が含まれます: '通知'、'Api'、'電子メール'、'Webhook'、'All'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはルールのローカライズの詳細な説明を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または規則の UI の表示名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtensionName">
      <MemberSignature Language="C#" Value="public string ExtensionName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExtensionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ExtensionName" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtensionName As String" />
      <MemberSignature Language="F#" Value="member this.ExtensionName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ExtensionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extensionName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            拡張機能の設定を取得または存在する場合は、ポータルの名前。 ダイナミック ルールのみに適用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardLink">
      <MemberSignature Language="C#" Value="public string ForwardLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ForwardLink" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardLink As String" />
      <MemberSignature Language="F#" Value="member this.ForwardLink : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ForwardLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="forwardLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または転送リンクをルールに関連付けられている外部ドキュメントに設定します。 ダイナミック ルールのみに適用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isDynamic")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、これは、動的に追加された規則に関連付ける場合は true。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As Nullable(Of NotificationLevel)" />
      <MemberSignature Language="F#" Value="member this.Level : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、このルールは、重大度を示すへの影響のレベルを設定します。
            使用可能な値が含まれます: '重大'、'警告'、'情報'、'NonUrgentSuggestion'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはルール (UI に適している) のローカライズされた名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            取得またはルールの一意の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecommendationId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RecommendationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RecommendationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.RecommendationId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecommendationId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RecommendationId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.RecommendationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recommendationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または推奨設定が存在する場合、そのルールに関連付けられている推奨事項が関連付けられているオブジェクトの ID を設定します。
            設定されているようなオブジェクトが存在しない場合に null です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはルールを含むカテゴリのタグの配列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>