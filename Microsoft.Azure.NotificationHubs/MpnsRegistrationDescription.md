<Type Name="MpnsRegistrationDescription" FullName="Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription">
  <TypeSignature Language="C#" Value="public class MpnsRegistrationDescription : Microsoft.Azure.NotificationHubs.RegistrationDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MpnsRegistrationDescription extends Microsoft.Azure.NotificationHubs.RegistrationDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class MpnsRegistrationDescription&#xA;Inherits RegistrationDescription" />
  <TypeSignature Language="F#" Value="type MpnsRegistrationDescription = class&#xA;    inherit RegistrationDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.RegistrationDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="MpnsRegistrationDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>MPNS 登録の説明を提供します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsRegistrationDescription (Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription sourceRegistration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription sourceRegistration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription.#ctor(Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sourceRegistration As MpnsRegistrationDescription)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription : Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription -&gt; Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription sourceRegistration" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceRegistration" Type="Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription" />
      </Parameters>
      <Docs>
        <param name="sourceRegistration">登録のソース。</param>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsRegistrationDescription (string channelUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string channelUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (channelUri As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription : string -&gt; Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription channelUri" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="channelUri">チャネル URI です。</param>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsRegistrationDescription (Uri channelUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri channelUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (channelUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription : Uri -&gt; Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription channelUri" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="channelUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="channelUri">チャネル URI です。</param>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsRegistrationDescription (string channelUri, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string channelUri, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription.#ctor(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (channelUri As String, tags As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription : string * seq&lt;string&gt; -&gt; Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription (channelUri, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="channelUri">チャネル URI です。</param>
        <param name="tags">説明のタグ。</param>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsRegistrationDescription (Uri channelUri, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri channelUri, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription.#ctor(System.Uri,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (channelUri As Uri, tags As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription : Uri * seq&lt;string&gt; -&gt; Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription (channelUri, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="channelUri" Type="System.Uri" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="channelUri">チャネル URI です。</param>
        <param name="tags">説明のタグ。</param>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChannelUri">
      <MemberSignature Language="C#" Value="public Uri ChannelUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ChannelUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription.ChannelUri" />
      <MemberSignature Language="VB.NET" Value="Public Property ChannelUri As Uri" />
      <MemberSignature Language="F#" Value="member this.ChannelUri : Uri with get, set" Usage="Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription.ChannelUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="ChannelUri", Order=2001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはチャネル URI を設定します。</summary>
        <value>チャネル URI です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryTileName">
      <MemberSignature Language="C#" Value="public string SecondaryTileName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryTileName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription.SecondaryTileName" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryTileName As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryTileName : string with get, set" Usage="Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription.SecondaryTileName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="SecondaryTileName", Order=2002)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはセカンダリ タイルの名前を設定します。
            </summary>
        <value>
            セカンダリ タイルの名前。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>