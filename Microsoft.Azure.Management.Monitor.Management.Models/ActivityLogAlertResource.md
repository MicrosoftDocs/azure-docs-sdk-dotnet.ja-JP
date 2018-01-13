<Type Name="ActivityLogAlertResource" FullName="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource">
  <TypeSignature Language="C#" Value="public class ActivityLogAlertResource : Microsoft.Azure.Management.Monitor.Management.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActivityLogAlertResource extends Microsoft.Azure.Management.Monitor.Management.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource" />
  <TypeSignature Language="VB.NET" Value="Public Class ActivityLogAlertResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ActivityLogAlertResource = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Monitor.Management.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            アクティビティをログ アラート リソースです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityLogAlertResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ActivityLogAlertResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityLogAlertResource (string location, System.Collections.Generic.IList&lt;string&gt; scopes, Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition condition, Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList actions, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;bool&gt; enabled = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class System.Collections.Generic.IList`1&lt;string&gt; scopes, class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition condition, class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList actions, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;bool&gt; enabled, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.#ctor(System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition,Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, scopes As IList(Of String), condition As ActivityLogAlertAllOfCondition, actions As ActivityLogAlertActionList, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional enabled As Nullable(Of Boolean) = null, Optional description As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource : string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition * Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource (location, scopes, condition, actions, id, name, type, tags, enabled, description)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="scopes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="condition" Type="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition" />
        <Parameter Name="actions" Type="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">リソースの場所</param>
        <param name="scopes">プレフィックスとして使用されるリソース Id の一覧。 アラートは、これらのプレフィックスのいずれかに該当するリソース Id で activityLogs にのみ適用されます。 この一覧は、少なくとも 1 つの項目を含める必要があります。</param>
        <param name="condition">アクティブ化するには、このアラートの原因となる条件です。</param>
        <param name="actions">条件が満たされたときにアクティブ化するアクションです。</param>
        <param name="id">Azure のリソース Id</param>
        <param name="name">Azure のリソース名</param>
        <param name="type">Azure リソースの種類</param>
        <param name="tags">リソース タグ</param>
        <param name="enabled">このアクティビティのログのアラートが有効になっているかどうかを示します。 アクティビティのログのアラートが有効でない場合、そのアクションのいずれもアクティブ化されます。</param>
        <param name="description">このアクティビティのログのアラートの説明です。</param>
        <summary>
            ActivityLogAlertResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Actions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList Actions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList Actions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Actions" />
      <MemberSignature Language="VB.NET" Value="Public Property Actions As ActivityLogAlertActionList" />
      <MemberSignature Language="F#" Value="member this.Actions : Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Actions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.actions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または条件が満たされたときに起動するアクションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Condition">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition Condition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition Condition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Condition" />
      <MemberSignature Language="VB.NET" Value="Public Property Condition As ActivityLogAlertAllOfCondition" />
      <MemberSignature Language="F#" Value="member this.Condition : Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Condition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.condition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアクティブ化するには、このアラートの原因となる条件を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、このアクティビティのログのアラートの説明を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、このアクティビティのログのアラートが有効になっているかどうかを示します。
            アクティビティのログのアラートが有効でない場合、そのアクションのいずれもアクティブ化されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scopes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Scopes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Scopes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Scopes" />
      <MemberSignature Language="VB.NET" Value="Public Property Scopes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Scopes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Scopes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scopes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、プレフィックスとして使用されるリソース Id の一覧を設定します。
            アラートは、これらのプレフィックスのいずれかに該当するリソース Id で activityLogs にのみ適用されます。 この一覧は、少なくとも 1 つの項目を含める必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="activityLogAlertResource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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