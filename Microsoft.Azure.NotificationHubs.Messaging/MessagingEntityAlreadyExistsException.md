<Type Name="MessagingEntityAlreadyExistsException" FullName="Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException">
  <TypeSignature Language="C#" Value="public sealed class MessagingEntityAlreadyExistsException : Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessagingEntityAlreadyExistsException extends Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessagingEntityAlreadyExistsException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type MessagingEntityAlreadyExistsException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>エラーが存在するメッセージング エンティティを既にシグナリングに対してスローされる例外を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEntityAlreadyExistsException (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (entityName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException entityName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName">エンティティの名前。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException" />エンティティの名前を持つクラス。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEntityAlreadyExistsException (string entityName, Microsoft.Azure.NotificationHubs.Tracing.TrackingContext trackingContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string entityName, class Microsoft.Azure.NotificationHubs.Tracing.TrackingContext trackingContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException.#ctor(System.String,Microsoft.Azure.NotificationHubs.Tracing.TrackingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException : string * Microsoft.Azure.NotificationHubs.Tracing.TrackingContext -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException (entityName, trackingContext)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="trackingContext" Type="Microsoft.Azure.NotificationHubs.Tracing.TrackingContext" />
      </Parameters>
      <Docs>
        <param name="entityName">エンティティの名前。</param>
        <param name="trackingContext">操作の追跡、トランザクションが関連付けられているコンテキスト情報。</param>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEntityAlreadyExistsException (string message, Microsoft.Azure.NotificationHubs.Tracing.TrackingContext trackingContext, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class Microsoft.Azure.NotificationHubs.Tracing.TrackingContext trackingContext, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException.#ctor(System.String,Microsoft.Azure.NotificationHubs.Tracing.TrackingContext,System.Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException : string * Microsoft.Azure.NotificationHubs.Tracing.TrackingContext * Exception -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException (message, trackingContext, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="trackingContext" Type="Microsoft.Azure.NotificationHubs.Tracing.TrackingContext" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">例外の原因を説明するエラー メッセージ。</param>
        <param name="trackingContext">操作の追跡、トランザクションが関連付けられているコンテキスト情報。</param>
        <param name="innerException">現在の例外の原因となった内部例外。</param>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="messagingEntityAlreadyExistsException.GetObjectData (info, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">スローされた例外に関するシリアル化されたオブジェクト データ。</param>
        <param name="context">転送元または変換先に関する文脈情報。</param>
        <summary>例外に関するデータをシリアル化情報を追加します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>