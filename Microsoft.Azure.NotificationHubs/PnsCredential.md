<Type Name="PnsCredential" FullName="Microsoft.Azure.NotificationHubs.PnsCredential">
  <TypeSignature Language="C#" Value="public abstract class PnsCredential : Microsoft.Azure.NotificationHubs.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit PnsCredential extends Microsoft.Azure.NotificationHubs.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class PnsCredential&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type PnsCredential = class&#xA;    inherit EntityDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Messaging.EntityDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="PnsCredential", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.AdmCredential))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.SmtpCredential))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.WnsCredential))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.NokiaXCredential))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.MpnsCredential))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.ApnsCredential))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.GcmCredential))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>PNS 資格情報を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BlockedOn">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; BlockedOn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; BlockedOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.PnsCredential.BlockedOn" />
      <MemberSignature Language="VB.NET" Value="Public Property BlockedOn As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.BlockedOn : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.PnsCredential.BlockedOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="BlockedOn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または この資格情報がブロックされている日付と時刻を設定します。</summary>
        <value>この資格情報がブロックされている日付と時刻。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsEqual">
      <MemberSignature Language="C#" Value="public static bool IsEqual (Microsoft.Azure.NotificationHubs.PnsCredential cred1, Microsoft.Azure.NotificationHubs.PnsCredential cred2);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsEqual(class Microsoft.Azure.NotificationHubs.PnsCredential cred1, class Microsoft.Azure.NotificationHubs.PnsCredential cred2) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.PnsCredential.IsEqual(Microsoft.Azure.NotificationHubs.PnsCredential,Microsoft.Azure.NotificationHubs.PnsCredential)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsEqual (cred1 As PnsCredential, cred2 As PnsCredential) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsEqual : Microsoft.Azure.NotificationHubs.PnsCredential * Microsoft.Azure.NotificationHubs.PnsCredential -&gt; bool" Usage="Microsoft.Azure.NotificationHubs.PnsCredential.IsEqual (cred1, cred2)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cred1" Type="Microsoft.Azure.NotificationHubs.PnsCredential" />
        <Parameter Name="cred2" Type="Microsoft.Azure.NotificationHubs.PnsCredential" />
      </Parameters>
      <Docs>
        <param name="cred1">比較する最初の資格情報です。</param>
        <param name="cred2">比較する 2 番目の資格情報です。</param>
        <summary>2 つの資格情報が等しいかどうかを指定します。</summary>
        <returns>2 つの資格情報が等しい場合は true。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="protected string this[string name] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.PnsCredential.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Protected Property Item(name As String) As String" />
      <MemberSignature Language="F#" Value="member this.Item(string) : string with get, set" Usage="Microsoft.Azure.NotificationHubs.PnsCredential.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">資格情報の名前です。</param>
        <summary>取得または、この資格情報に関連付けられている値を設定します。</summary>
        <value>この資格情報に関連付けられている値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidate">
      <MemberSignature Language="C#" Value="protected virtual void OnValidate (bool allowLocalMockPns);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnValidate(bool allowLocalMockPns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.PnsCredential.OnValidate(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnValidate (allowLocalMockPns As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member OnValidate : bool -&gt; unit&#xA;override this.OnValidate : bool -&gt; unit" Usage="pnsCredential.OnValidate allowLocalMockPns" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="allowLocalMockPns" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="allowLocalMockPns">ローカルのモック PNS; を許可する場合は trueそれ以外の場合は false です。</param>
        <summary>資格情報を検証します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Messaging.PnsCredentialProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.Messaging.PnsCredentialProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.PnsCredential.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As PnsCredentialProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.NotificationHubs.Messaging.PnsCredentialProperties with get, set" Usage="Microsoft.Azure.NotificationHubs.PnsCredential.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.PnsCredentialProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または、この資格情報のプロパティを設定します。</summary>
        <value>この資格情報のプロパティです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>