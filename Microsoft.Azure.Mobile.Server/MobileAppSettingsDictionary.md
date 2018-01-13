<Type Name="MobileAppSettingsDictionary" FullName="Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary">
  <TypeSignature Language="C#" Value="public class MobileAppSettingsDictionary : System.Collections.Generic.Dictionary&lt;string,string&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit MobileAppSettingsDictionary extends System.Collections.Generic.Dictionary`2&lt;string, string&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileAppSettingsDictionary&#xA;Inherits Dictionary(Of String, String)" />
  <TypeSignature Language="F#" Value="type MobileAppSettingsDictionary = class&#xA;    inherit Dictionary&lt;string, string&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.String</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="!1">System.String</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Usage", "CA2240:ImplementISerializableCorrectly", Justification="Not intended for serialization")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            設定を含む接続文字列、サブスクリプション ID に、ホスト名などのサービスなどです。<see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" />などの既知の設定の型指定されたプロパティを提供<see cref="M:HostName" />と<see cref="M:SubscriptionId" />だけでなく<see cref="T:System.Collections.Generic.IDictionary`2" />他のすべての設定にアクセスします。
            </summary>
    <remarks>インスタンスで設定されたプロパティの値のみに留まり有効で、現在の有効期間にわたって<see cref="T:System.AppDomain" />です。
            永続的な方法で、設定を変更するには、サービス ホストによって提供されるメカニズムを使用して更新してください。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileAppSettingsDictionary ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MobileAppSettingsDictionary (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" Usage="new Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">A<see cref="T:System.Runtime.Serialization.SerializationInfo" />に関する情報を含む、<see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" />初期化されるようにします。</param>
        <param name="context">A<see cref="T:System.Runtime.Serialization.StreamingContext" />シリアル化ストリームのソースの変換先およびコンテキスト情報を示すです。</param>
        <summary>
            指定したシリアル化情報とストリーム コンテキストを使用して、<see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Connections">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Mobile.Server.ConnectionSettings&gt; Connections { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Mobile.Server.ConnectionSettings&gt; Connections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.Connections" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Connections As IDictionary(Of String, ConnectionSettings)" />
      <MemberSignature Language="F#" Value="member this.Connections : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Mobile.Server.ConnectionSettings&gt;" Usage="Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.Connections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Mobile.Server.ConnectionSettings&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービスの接続文字列のセットを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public virtual string HostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.HostName" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string with get, set" Usage="Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサービスのホスト名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public string this[string key] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(key As String) As String" />
      <MemberSignature Language="F#" Value="member this.Item(string) : string with get, set" Usage="Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">取得または設定する値のキー。</param>
        <summary>
            指定されたキーに関連付けられている値を取得または設定します。
            </summary>
        <value>指定されたキーに関連付けられている値。 指定したキーが見つからなかった場合、get 操作は <see cref="T:System.Collections.Generic.KeyNotFoundException" /> をスローし、set 操作は指定したキーを持つ新しい要素を作成します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationHubName">
      <MemberSignature Language="C#" Value="public virtual string NotificationHubName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NotificationHubName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.NotificationHubName" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property NotificationHubName As String" />
      <MemberSignature Language="F#" Value="member this.NotificationHubName : string with get, set" Usage="Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.NotificationHubName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプッシュ通知を処理するためには、このサービスに関連付けられた通知ハブの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SkipVersionCheck">
      <MemberSignature Language="C#" Value="public virtual bool SkipVersionCheck { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SkipVersionCheck" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.SkipVersionCheck" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property SkipVersionCheck As Boolean" />
      <MemberSignature Language="F#" Value="member this.SkipVersionCheck : bool with get, set" Usage="Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.SkipVersionCheck" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または MobileApp コント ローラーへのすべての呼び出しの ZUMO API バージョン ヘッダーのチェックはスキップするかどうかを示す値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public virtual string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサービスのサブスクリプション Id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>