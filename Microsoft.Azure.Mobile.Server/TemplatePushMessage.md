<Type Name="TemplatePushMessage" FullName="Microsoft.Azure.Mobile.Server.TemplatePushMessage">
  <TypeSignature Language="C#" Value="public class TemplatePushMessage : System.Collections.Generic.Dictionary&lt;string,string&gt;, Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit TemplatePushMessage extends System.Collections.Generic.Dictionary`2&lt;string, string&gt; implements class Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" />
  <TypeSignature Language="VB.NET" Value="Public Class TemplatePushMessage&#xA;Inherits Dictionary(Of String, String)&#xA;Implements IPushMessage" />
  <TypeSignature Language="F#" Value="type TemplatePushMessage = class&#xA;    inherit Dictionary&lt;string, string&gt;&#xA;    interface IPushMessage" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.String</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="!1">System.String</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Mobile.Server.Notifications.IPushMessage</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1710:IdentifiersShouldHaveCorrectSuffix", Justification="This describes a message.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />テンプレート登録に登録したデバイスを対象とする通知のペイロードを生成するのに役立ちます。 テンプレートには、送信者に入力する必要があるキーワードのセットを含むを受信する通知の形状を指定する、デバイスことができます。 全体の通知を構築、送信者の代わりには、単にキーワードの値を設定します。 通知ハブは、デバイスと、送信側によって提供されるキーワードによって登録されている特定のテンプレートを使用して通知を作成し、します。 これは、プラットフォームに関係なく、受信側の通知を送信するより簡単です。 定義されているキーワード、<see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" />クラスを使用して送信することができます、<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" />クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TemplatePushMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TemplatePushMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TemplatePushMessage (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TemplatePushMessage.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.TemplatePushMessage : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Mobile.Server.TemplatePushMessage" Usage="new Microsoft.Azure.Mobile.Server.TemplatePushMessage (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">A<see cref="T:System.Runtime.Serialization.SerializationInfo" />に関する情報を含む、<see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" />初期化されるようにします。</param>
        <param name="context">A<see cref="T:System.Runtime.Serialization.StreamingContext" />シリアル化ストリームのソースの変換先およびコンテキスト情報を示すです。</param>
        <summary>
            指定したシリアル化情報とストリーム コンテキストを使用して、<see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>