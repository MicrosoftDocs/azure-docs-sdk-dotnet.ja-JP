<Type Name="RuleWebhookAction" FullName="Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction">
  <TypeSignature Language="C#" Value="public class RuleWebhookAction : Microsoft.Azure.Management.Monitor.Management.Models.RuleAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RuleWebhookAction extends Microsoft.Azure.Management.Monitor.Management.Models.RuleAction" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction" />
  <TypeSignature Language="VB.NET" Value="Public Class RuleWebhookAction&#xA;Inherits RuleAction" />
  <TypeSignature Language="F#" Value="type RuleWebhookAction = class&#xA;    inherit RuleAction" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Monitor.Management.Models.RuleAction</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Azure.Management.Insights.Models.RuleWebhookAction")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            ルールの条件が評価されるときに、サービスに投稿するアクションを指定します。 識別子は常に RuleWebhookAction ここでです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleWebhookAction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction.#ctor" />
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
            RuleWebhookAction クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleWebhookAction (string serviceUri = null, System.Collections.Generic.IDictionary&lt;string,string&gt; properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceUri, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction.#ctor(System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceUri As String = null, Optional properties As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction : string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction (serviceUri, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.String" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceUri">アラートがアクティブ化や解決時に、通知をポストするサービスの uri。</param>
        <param name="properties">post 操作に含めるカスタム プロパティのディクショナリ。 Webhook ペイロードには、これらのデータが追加されます。</param>
        <summary>
            RuleWebhookAction クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または post 操作に含めるカスタム プロパティのディクショナリを設定します。 Webhook ペイロードには、これらのデータが追加されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceUri">
      <MemberSignature Language="C#" Value="public string ServiceUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction.ServiceUri" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceUri As String" />
      <MemberSignature Language="F#" Value="member this.ServiceUri : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction.ServiceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアラートがアクティブ化や解決時に、通知をポストするサービスの uri を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>