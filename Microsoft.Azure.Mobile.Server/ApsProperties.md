<Type Name="ApsProperties" FullName="Microsoft.Azure.Mobile.Server.ApsProperties">
  <TypeSignature Language="C#" Value="public class ApsProperties : System.Collections.Generic.Dictionary&lt;string,object&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit ApsProperties extends System.Collections.Generic.Dictionary`2&lt;string, object&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.ApsProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class ApsProperties&#xA;Inherits Dictionary(Of String, Object)" />
  <TypeSignature Language="F#" Value="type ApsProperties = class&#xA;    inherit Dictionary&lt;string, obj&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.Generic.Dictionary&lt;System.String,System.Object&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.String</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="!1">System.Object</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1710:IdentifiersShouldHaveCorrectSuffix", Justification="This is a property bag.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            "Aps"プロパティには、Apple Push Notification サービス (APNS) を対象とする通知の定義が含まれています。 使用するものでは、<see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApsProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.ApsProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Mobile.Server.ApsProperties" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ApsProperties (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.ApsProperties.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.ApsProperties : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Mobile.Server.ApsProperties" Usage="new Microsoft.Azure.Mobile.Server.ApsProperties (info, context)" />
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
        <param name="info">A<see cref="T:System.Runtime.Serialization.SerializationInfo" />に関する情報を含む、<see cref="T:Microsoft.Azure.Mobile.Server.ApsProperties" />初期化されるようにします。</param>
        <param name="context">A<see cref="T:System.Runtime.Serialization.StreamingContext" />シリアル化ストリームのソースの変換先およびコンテキスト情報を示すです。</param>
        <summary>
            指定したシリアル化情報とストリーム コンテキストを使用して、<see cref="T:Microsoft.Azure.Mobile.Server.ApsProperties" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Alert">
      <MemberSignature Language="C#" Value="public string Alert { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Alert" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApsProperties.Alert" />
      <MemberSignature Language="VB.NET" Value="Public Property Alert As String" />
      <MemberSignature Language="F#" Value="member this.Alert : string with get, set" Usage="Microsoft.Azure.Mobile.Server.ApsProperties.Alert" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            1 つの文字列として、警告メッセージ。 複雑な警告メッセージ オプション、使用<see cref="M:AlertProperties" />です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlertProperties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Mobile.Server.AlertProperties AlertProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Mobile.Server.AlertProperties AlertProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApsProperties.AlertProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AlertProperties As AlertProperties" />
      <MemberSignature Language="F#" Value="member this.AlertProperties : Microsoft.Azure.Mobile.Server.AlertProperties" Usage="Microsoft.Azure.Mobile.Server.ApsProperties.AlertProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.AlertProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            画像の表示などをローカライズ情報などのアラートを説明する追加のプロパティを含むディクショナリとしての警告メッセージ。このアラートは単なる文字列を使用してください場合<see cref="M:Alert" />です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Badge">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Badge { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Badge" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApsProperties.Badge" />
      <MemberSignature Language="VB.NET" Value="Public Property Badge As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Badge : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Mobile.Server.ApsProperties.Badge" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリケーション アイコンのバッジとして表示する数値。 このプロパティがない場合、バッジは変更されません。 バッジを削除するには、このプロパティの値を 0 に設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentAvailable">
      <MemberSignature Language="C#" Value="public bool ContentAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ContentAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApsProperties.ContentAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentAvailable As Boolean" />
      <MemberSignature Language="F#" Value="member this.ContentAvailable : bool with get, set" Usage="Microsoft.Azure.Mobile.Server.ApsProperties.ContentAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            新しいコンテンツが利用可能なことを示す 1 の値を持つこのキーを提供します。 Newsstand アプリをサポートするのに使用し、バック グラウンドのコンテンツをダウンロードします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sound">
      <MemberSignature Language="C#" Value="public string Sound { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sound" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApsProperties.Sound" />
      <MemberSignature Language="VB.NET" Value="Public Property Sound As String" />
      <MemberSignature Language="F#" Value="member this.Sound : string with get, set" Usage="Microsoft.Azure.Mobile.Server.ApsProperties.Sound" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリケーション バンドルのサウンド ファイルの名前。 このファイルのサウンドは警告として再生されます。 サウンド ファイルが存在しないか、既定値が値として指定された場合、は、既定のアラート サウンドが再生されます。 オーディオは、システム サウンド; と互換性があるオーディオ データ形式のいずれかである必要があります。 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>