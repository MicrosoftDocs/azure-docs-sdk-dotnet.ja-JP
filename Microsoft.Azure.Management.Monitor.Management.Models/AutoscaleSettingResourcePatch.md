<Type Name="AutoscaleSettingResourcePatch" FullName="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch">
  <TypeSignature Language="C#" Value="public class AutoscaleSettingResourcePatch" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoscaleSettingResourcePatch extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoscaleSettingResourcePatch" />
  <TypeSignature Language="F#" Value="type AutoscaleSettingResourcePatch = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
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
            Patch 操作用の自動スケール設定オブジェクト。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoscaleSettingResourcePatch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.#ctor" />
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
            AutoscaleSettingResourcePatch クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoscaleSettingResourcePatch (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; profiles, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; notifications = null, Nullable&lt;bool&gt; enabled = null, string name = null, string targetResourceUri = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; profiles, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; notifications, valuetype System.Nullable`1&lt;bool&gt; enabled, string name, string targetResourceUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile},System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification},System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (profiles As IList(Of AutoscaleProfile), Optional tags As IDictionary(Of String, String) = null, Optional notifications As IList(Of AutoscaleNotification) = null, Optional enabled As Nullable(Of Boolean) = null, Optional name As String = null, Optional targetResourceUri As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; * Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch (profiles, tags, notifications, enabled, name, targetResourceUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="profiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt;" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="notifications" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt;" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="targetResourceUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="profiles">異なる期間に対して異なるスケーリング パラメーターを指定する自動スケーリング プロファイルのコレクション。 最大 20 のプロファイルを指定できます。</param>
        <param name="tags">リソース タグ</param>
        <param name="notifications">通知のコレクション。</param>
        <param name="enabled">有効なフラグです。 リソースの自動スケーリングが有効になっているかどうかを指定します。 既定値は 'true' です。</param>
        <param name="name">自動スケール設定の名前。</param>
        <param name="targetResourceUri">自動スケール設定を追加するリソースのリソースの識別子です。</param>
        <summary>
            AutoscaleSettingResourcePatch クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Enabled" />
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
            取得または有効なフラグを設定します。 リソースの自動スケーリングが有効になっているかどうかを指定します。 既定値は 'true' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または自動スケール設定の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Notifications">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; Notifications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; Notifications" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Notifications" />
      <MemberSignature Language="VB.NET" Value="Public Property Notifications As IList(Of AutoscaleNotification)" />
      <MemberSignature Language="F#" Value="member this.Notifications : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Notifications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.notifications")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または通知のコレクションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Profiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; Profiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; Profiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Profiles" />
      <MemberSignature Language="VB.NET" Value="Public Property Profiles As IList(Of AutoscaleProfile)" />
      <MemberSignature Language="F#" Value="member this.Profiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Profiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.profiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または異なる期間に対して異なるスケーリング パラメーターを指定する自動スケーリング プロファイルのコレクションを設定します。 最大 20 のプロファイルを指定できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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
            取得またはリソース タグを設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceUri">
      <MemberSignature Language="C#" Value="public string TargetResourceUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.TargetResourceUri" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceUri As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceUri : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.TargetResourceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetResourceUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または自動スケール設定を追加するリソースのリソース識別子を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResourcePatch.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="autoscaleSettingResourcePatch.Validate " />
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