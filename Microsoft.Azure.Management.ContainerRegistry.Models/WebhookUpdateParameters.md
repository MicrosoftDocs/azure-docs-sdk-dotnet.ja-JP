<Type Name="WebhookUpdateParameters" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters">
  <TypeSignature Language="C#" Value="public class WebhookUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebhookUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class WebhookUpdateParameters" />
  <TypeSignature Language="F#" Value="type WebhookUpdateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Webhook を更新するためのパラメーターです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebhookUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            WebhookUpdateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebhookUpdateParameters (System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string serviceUri = null, System.Collections.Generic.IDictionary&lt;string,string&gt; customHeaders = null, string status = null, string scope = null, System.Collections.Generic.IList&lt;string&gt; actions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string serviceUri, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; customHeaders, string status, string scope, class System.Collections.Generic.IList`1&lt;string&gt; actions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional tags As IDictionary(Of String, String) = null, Optional serviceUri As String = null, Optional customHeaders As IDictionary(Of String, String) = null, Optional status As String = null, Optional scope As String = null, Optional actions As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters : System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters (tags, serviceUri, customHeaders, status, scope, actions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="serviceUri" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="actions" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="tags">Webhook のタグ。</param>
        <param name="serviceUri">サービスの通知を送信する webhook の URI です。</param>
        <param name="customHeaders">Webhook 通知に追加されるカスタム ヘッダー。</param>
        <param name="status">操作が呼び出されたときに webhook の状態です。 使用可能な値が含まれます: 'enabled'、'disabled'</param>
        <param name="scope">イベントをトリガーできますリポジトリのスコープです。 たとえば、' foo: *' リポジトリ foo 下にあるすべてのタグ イベントのことを意味します。 'foo:bar' は、'foo:bar' のみのイベントを意味します。 'foo' は、'foo:latest' と同じです。 空では、すべてのイベントを意味します。</param>
        <param name="actions">通知を送信する webhook をトリガーするアクションの一覧。</param>
        <summary>
            WebhookUpdateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Actions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Actions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Actions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.Actions" />
      <MemberSignature Language="VB.NET" Value="Public Property Actions As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Actions : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.Actions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.actions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または通知を送信する webhook をトリガーするアクションの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; CustomHeaders { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; CustomHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.CustomHeaders" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomHeaders As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.CustomHeaders : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.CustomHeaders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customHeaders")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または webhook 通知に追加されるカスタム ヘッダーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public string Scope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.Scope" />
      <MemberSignature Language="VB.NET" Value="Public Property Scope As String" />
      <MemberSignature Language="F#" Value="member this.Scope : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scope")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはイベントをトリガーできますリポジトリのスコープを設定します。 たとえば、' foo: *' リポジトリ foo 下にあるすべてのタグ イベントのことを意味します。 'foo:bar' は、'foo:bar' のみのイベントを意味します。 'foo' は、'foo:latest' と同じです。 空では、すべてのイベントを意味します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceUri">
      <MemberSignature Language="C#" Value="public string ServiceUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.ServiceUri" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceUri As String" />
      <MemberSignature Language="F#" Value="member this.ServiceUri : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.ServiceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサービスの通知を送信する webhook の URI を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または操作が呼び出された時点で、webhook の状態を設定します。 使用可能な値が含まれます: 'enabled'、'disabled'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または webhook のタグを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>