<Type Name="InstallationTemplate" FullName="Microsoft.Azure.NotificationHubs.InstallationTemplate">
  <TypeSignature Language="C#" Value="public class InstallationTemplate" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InstallationTemplate extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.InstallationTemplate" />
  <TypeSignature Language="VB.NET" Value="Public Class InstallationTemplate" />
  <TypeSignature Language="F#" Value="type InstallationTemplate = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject(ItemRequired=Newtonsoft.Json.Required.Default, MemberSerialization=Newtonsoft.Json.MemberSerialization.OptOut)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="81139-101">インスタンスに属する可能性がありますを表すテンプレート<see cref="T:Microsoft.Azure.NotificationHubs.Installation" />クラス</span><span class="sxs-lookup"><span data-stu-id="81139-101">Represents template which may belong to an instance of <see cref="T:Microsoft.Azure.NotificationHubs.Installation" /> class</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InstallationTemplate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.InstallationTemplate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public string Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.InstallationTemplate.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As String" />
      <MemberSignature Language="F#" Value="member this.Body : string with get, set" Usage="Microsoft.Azure.NotificationHubs.InstallationTemplate.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="body")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81139-102">取得または送信操作中に実際のデータを使用して入力をプレース ホルダーを含むことが通知のペイロードのテンプレート本体の設定</span><span class="sxs-lookup"><span data-stu-id="81139-102">Gets or sets a template body for notification payload which may contain placeholders to be filled in with actual data during the send operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expiry">
      <MemberSignature Language="C#" Value="public string Expiry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Expiry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.InstallationTemplate.Expiry" />
      <MemberSignature Language="VB.NET" Value="Public Property Expiry As String" />
      <MemberSignature Language="F#" Value="member this.Expiry : string with get, set" Usage="Microsoft.Azure.NotificationHubs.InstallationTemplate.Expiry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="expiry")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81139-103">取得または設定の有効期限を APNS を対象とした通知の適用</span><span class="sxs-lookup"><span data-stu-id="81139-103">Gets or sets expiry applicable for APNS-targeted notifications</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Headers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.InstallationTemplate.Headers" />
      <MemberSignature Language="VB.NET" Value="Public Property Headers As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Headers : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.InstallationTemplate.Headers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="headers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81139-104">MPNS を対象とした通知の該当するヘッダーのセットのコレクションを取得または</span><span class="sxs-lookup"><span data-stu-id="81139-104">Gets or set collection of headers applicable for MPNS-targeted notifications</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.InstallationTemplate.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.InstallationTemplate.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81139-105">取得または特定のテンプレートのタグのコレクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="81139-105">Gets or sets collection of tags for particular template.</span></span> <span data-ttu-id="81139-106">Ususaly 1 つのタグ (テンプレート名) は、ここにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="81139-106">Ususaly only one tag (template name) should be here.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>