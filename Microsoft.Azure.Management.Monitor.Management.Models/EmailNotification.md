<Type Name="EmailNotification" FullName="Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification">
  <TypeSignature Language="C#" Value="public class EmailNotification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EmailNotification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification" />
  <TypeSignature Language="VB.NET" Value="Public Class EmailNotification" />
  <TypeSignature Language="F#" Value="type EmailNotification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            自動スケール イベントの通知を電子メールで送信します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EmailNotification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification.#ctor" />
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
            EmailNotification クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EmailNotification (Nullable&lt;bool&gt; sendToSubscriptionAdministrator = null, Nullable&lt;bool&gt; sendToSubscriptionCoAdministrators = null, System.Collections.Generic.IList&lt;string&gt; customEmails = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; sendToSubscriptionAdministrator, valuetype System.Nullable`1&lt;bool&gt; sendToSubscriptionCoAdministrators, class System.Collections.Generic.IList`1&lt;string&gt; customEmails) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification.#ctor(System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional sendToSubscriptionAdministrator As Nullable(Of Boolean) = null, Optional sendToSubscriptionCoAdministrators As Nullable(Of Boolean) = null, Optional customEmails As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification : Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification (sendToSubscriptionAdministrator, sendToSubscriptionCoAdministrators, customEmails)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sendToSubscriptionAdministrator" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="sendToSubscriptionCoAdministrators" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customEmails" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="sendToSubscriptionAdministrator">サブスクリプションの管理者に電子メールを送信するかどうかを示す値。</param>
        <param name="sendToSubscriptionCoAdministrators">サブスクリプションの共同管理者に電子メールを送信するかどうかを示す値。</param>
        <param name="customEmails">カスタムの電子メールの一覧です。 この値できます null または空である場合にこの属性は無視されます。</param>
        <summary>
            EmailNotification クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomEmails">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; CustomEmails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; CustomEmails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification.CustomEmails" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomEmails As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.CustomEmails : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification.CustomEmails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="customEmails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはカスタムの電子メール ボックスの一覧を設定します。 この値できます null または空である場合にこの属性は無視されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendToSubscriptionAdministrator">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SendToSubscriptionAdministrator { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SendToSubscriptionAdministrator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification.SendToSubscriptionAdministrator" />
      <MemberSignature Language="VB.NET" Value="Public Property SendToSubscriptionAdministrator As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SendToSubscriptionAdministrator : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification.SendToSubscriptionAdministrator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sendToSubscriptionAdministrator")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブスクリプションの管理者に電子メールを送信するかどうかを示す値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendToSubscriptionCoAdministrators">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SendToSubscriptionCoAdministrators { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SendToSubscriptionCoAdministrators" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification.SendToSubscriptionCoAdministrators" />
      <MemberSignature Language="VB.NET" Value="Public Property SendToSubscriptionCoAdministrators As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SendToSubscriptionCoAdministrators : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification.SendToSubscriptionCoAdministrators" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sendToSubscriptionCoAdministrators")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブスクリプションの共同管理者に電子メールを送信するかどうかを示す値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>