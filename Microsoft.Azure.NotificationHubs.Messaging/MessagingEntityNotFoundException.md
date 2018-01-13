<Type Name="MessagingEntityNotFoundException" FullName="Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException">
  <TypeSignature Language="C#" Value="public sealed class MessagingEntityNotFoundException : Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessagingEntityNotFoundException extends Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessagingEntityNotFoundException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type MessagingEntityNotFoundException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>メッセージング エンティティの信号に対してスローされる例外には、エラーで見つかりませんでした。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEntityNotFoundException (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (entityName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException entityName" />
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
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException" />エンティティ名を持つクラス。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEntityNotFoundException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException : string * Exception -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">例外の原因を説明するエラー メッセージ。</param>
        <param name="innerException">現在の例外の原因となった例外。</param>
        <summary>指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="messagingEntityNotFoundException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>現在の例外の文字列表現を返します。</summary>
        <returns>現在の例外の文字列形式。</returns>
        <remarks>To be added.</remarks>
        <PermissionSet>
          <IPermission class="System.Security.Permissions.FileIOPermission, mscorlib, Version=2.0.3600.0, Culture=neutral, PublicKeyToken=b77a5c561934e089" version="1" PathDiscovery="*AllFiles*" />
        </PermissionSet>
      </Docs>
    </Member>
  </Members>
</Type>