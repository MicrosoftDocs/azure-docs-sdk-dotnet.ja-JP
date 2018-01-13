<Type Name="Webhook" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.Webhook">
  <TypeSignature Language="C#" Value="public class Webhook : Microsoft.Azure.Management.ContainerRegistry.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Webhook extends Microsoft.Azure.Management.ContainerRegistry.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.Webhook" />
  <TypeSignature Language="VB.NET" Value="Public Class Webhook&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Webhook = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ContainerRegistry.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            コンテナー レジストリの webhook を表すオブジェクト。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Webhook ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Webhook クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Webhook (string location, System.Collections.Generic.IList&lt;string&gt; actions, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string status = null, string scope = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class System.Collections.Generic.IList`1&lt;string&gt; actions, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string status, string scope, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.#ctor(System.String,System.Collections.Generic.IList{System.String},System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, actions As IList(Of String), Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional status As String = null, Optional scope As String = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.Webhook : string * System.Collections.Generic.IList&lt;string&gt; * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Webhook" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.Webhook (location, actions, id, name, type, tags, status, scope, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="actions" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">リソースの場所です。 これは、リソースを作成した後に変更できません。</param>
        <param name="actions">通知を送信する webhook をトリガーするアクションの一覧。</param>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前。</param>
        <param name="type">リソースの型。</param>
        <param name="tags">リソースのタグ。</param>
        <param name="status">操作が呼び出されたときに webhook の状態です。 使用可能な値が含まれます: 'enabled'、'disabled'</param>
        <param name="scope">イベントをトリガーできますリポジトリのスコープです。 たとえば、' foo: *' リポジトリ foo 下にあるすべてのタグ イベントのことを意味します。 'foo:bar' は、'foo:bar' のみのイベントを意味します。 'foo' は、'foo:latest' と同じです。 空では、すべてのイベントを意味します。</param>
        <param name="provisioningState">操作が呼び出されたときに webhook のプロビジョニングの状態。 使用可能な値が含まれます: '作成中'、'更新'、'削除'、'成功'、'失敗'、'キャンセル'</param>
        <summary>
            Webhook クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Actions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Actions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Actions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.Actions" />
      <MemberSignature Language="VB.NET" Value="Public Property Actions As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Actions : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.Actions" />
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
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            操作が呼び出された時点で、webhook のプロビジョニングの状態を取得します。 使用可能な値が含まれます: '作成中'、'更新'、'削除'、'成功'、'失敗'、'キャンセル'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public string Scope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.Scope" />
      <MemberSignature Language="VB.NET" Value="Public Property Scope As String" />
      <MemberSignature Language="F#" Value="member this.Scope : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.Scope" />
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
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.Status" />
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
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="webhook.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
  </Members>
</Type>