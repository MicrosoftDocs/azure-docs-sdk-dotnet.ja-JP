<Type Name="AlertProperties" FullName="Microsoft.Azure.Mobile.Server.AlertProperties">
  <TypeSignature Language="C#" Value="public class AlertProperties : System.Collections.Generic.Dictionary&lt;string,object&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit AlertProperties extends System.Collections.Generic.Dictionary`2&lt;string, object&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.AlertProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class AlertProperties&#xA;Inherits Dictionary(Of String, Object)" />
  <TypeSignature Language="F#" Value="type AlertProperties = class&#xA;    inherit Dictionary&lt;string, obj&gt;" />
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
            「警告」プロパティには、Apple Push Notification サービス (APNS) を対象とする通知の警告に固有のプロパティが含まれています。 使用するものでは、<see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AlertProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.AlertProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Mobile.Server.AlertProperties" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected AlertProperties (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.AlertProperties.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.AlertProperties : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Mobile.Server.AlertProperties" Usage="new Microsoft.Azure.Mobile.Server.AlertProperties (info, context)" />
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
        <param name="info">A<see cref="T:System.Runtime.Serialization.SerializationInfo" />に関する情報を含む、<see cref="T:Microsoft.Azure.Mobile.Server.AlertProperties" />初期化されるようにします。</param>
        <param name="context">A<see cref="T:System.Runtime.Serialization.StreamingContext" />シリアル化ストリームのソースの変換先およびコンテキスト情報を示すです。</param>
        <summary>
            指定したシリアル化情報とストリーム コンテキストを使用して、<see cref="T:Microsoft.Azure.Mobile.Server.AlertProperties" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionLocKey">
      <MemberSignature Language="C#" Value="public string ActionLocKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActionLocKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.AlertProperties.ActionLocKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionLocKey As String" />
      <MemberSignature Language="F#" Value="member this.ActionLocKey : string with get, set" Usage="Microsoft.Azure.Mobile.Server.AlertProperties.ActionLocKey" />
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
            文字列が指定されている場合は、2 つのボタンのアラートが表示されます。 文字列は、現在のローカリゼーション"View"の代わりに、右のボタンのタイトルに使用するローカライズされた文字列を取得するキーとして使用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public string Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.AlertProperties.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As String" />
      <MemberSignature Language="F#" Value="member this.Body : string with get, set" Usage="Microsoft.Azure.Mobile.Server.AlertProperties.Body" />
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
            警告メッセージのテキストです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LaunchImage">
      <MemberSignature Language="C#" Value="public string LaunchImage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LaunchImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.AlertProperties.LaunchImage" />
      <MemberSignature Language="VB.NET" Value="Public Property LaunchImage As String" />
      <MemberSignature Language="F#" Value="member this.LaunchImage : string with get, set" Usage="Microsoft.Azure.Mobile.Server.AlertProperties.LaunchImage" />
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
            アプリケーション バンドル; でイメージ ファイルのファイル名拡張子を含めることがあります、これを省略またはことができます。 イメージは、ユーザーのアクション ボタンをタップまたはスライダーをアクションと起動イメージとして使用されます。 このプロパティが指定されていない場合、システムが、前のスナップショットを使用して、アプリケーションの UILaunchImageFile キーによって識別されるイメージを使用して<c>Info.plist</c>ファイル、またはフォールバックして<c>Default.png</c>.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocKey">
      <MemberSignature Language="C#" Value="public string LocKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.AlertProperties.LocKey" />
      <MemberSignature Language="VB.NET" Value="Public Property LocKey As String" />
      <MemberSignature Language="F#" Value="member this.LocKey : string with get, set" Usage="Microsoft.Azure.Mobile.Server.AlertProperties.LocKey" />
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
            アラート メッセージ文字列にキー、 <c>Localizable.strings</c> (これは、ユーザーの言語設定によって設定されます) 現在のローカライズ用のファイルです。 キーの文字列でフォーマットできます。 <c> %@ </c>と<c> %n$@ </c>指定子で指定された変数を<c>loc args</c>です。 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogArgs">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;string&gt; LogArgs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;string&gt; LogArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.AlertProperties.LogArgs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LogArgs As Collection(Of String)" />
      <MemberSignature Language="F#" Value="member this.LogArgs : System.Collections.ObjectModel.Collection&lt;string&gt;" Usage="Microsoft.Azure.Mobile.Server.AlertProperties.LogArgs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            変数の文字列値の書式指定子の代わりに表示を<c>loc キー</c>です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>