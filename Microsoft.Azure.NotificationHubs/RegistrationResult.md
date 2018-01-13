<Type Name="RegistrationResult" FullName="Microsoft.Azure.NotificationHubs.RegistrationResult">
  <TypeSignature Language="C#" Value="public sealed class RegistrationResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RegistrationResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.RegistrationResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RegistrationResult" />
  <TypeSignature Language="F#" Value="type RegistrationResult = class" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="RegistrationResult", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>登録の結果を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegistrationResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RegistrationResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.RegistrationResult" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPlatform">
      <MemberSignature Language="C#" Value="public string ApplicationPlatform { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationPlatform" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RegistrationResult.ApplicationPlatform" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPlatform As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationPlatform : string with get, set" Usage="Microsoft.Azure.NotificationHubs.RegistrationResult.ApplicationPlatform" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="ApplicationPlatform", Order=1001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはアプリケーションのプラットフォームを設定します。</summary>
        <value>アプリケーション プラットフォームです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Outcome">
      <MemberSignature Language="C#" Value="public string Outcome { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Outcome" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RegistrationResult.Outcome" />
      <MemberSignature Language="VB.NET" Value="Public Property Outcome As String" />
      <MemberSignature Language="F#" Value="member this.Outcome : string with get, set" Usage="Microsoft.Azure.NotificationHubs.RegistrationResult.Outcome" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, Name="Outcome", Order=1004)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または登録の結果を設定します。</summary>
        <value>登録の結果です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PnsHandle">
      <MemberSignature Language="C#" Value="public string PnsHandle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PnsHandle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RegistrationResult.PnsHandle" />
      <MemberSignature Language="VB.NET" Value="Public Property PnsHandle As String" />
      <MemberSignature Language="F#" Value="member this.PnsHandle : string with get, set" Usage="Microsoft.Azure.NotificationHubs.RegistrationResult.PnsHandle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="PnsHandle", Order=1002)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または PNS ハンドルを設定します。</summary>
        <value>PNS が処理されます。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrationId">
      <MemberSignature Language="C#" Value="public string RegistrationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegistrationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RegistrationResult.RegistrationId" />
      <MemberSignature Language="VB.NET" Value="Public Property RegistrationId As String" />
      <MemberSignature Language="F#" Value="member this.RegistrationId : string with get, set" Usage="Microsoft.Azure.NotificationHubs.RegistrationResult.RegistrationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="RegistrationId", Order=1003)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定登録 id。</summary>
        <value>登録 id。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>