<Type Name="NotificationHubDescription" FullName="Microsoft.Azure.NotificationHubs.NotificationHubDescription">
  <TypeSignature Language="C#" Value="public sealed class NotificationHubDescription : Microsoft.Azure.NotificationHubs.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NotificationHubDescription extends Microsoft.Azure.NotificationHubs.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NotificationHubDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type NotificationHubDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="NotificationHubDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>通知ハブの説明を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotificationHubDescription (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NotificationHubDescription : string -&gt; Microsoft.Azure.NotificationHubs.NotificationHubDescription" Usage="new Microsoft.Azure.NotificationHubs.NotificationHubDescription path" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">説明のパス。</param>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdmCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.AdmCredential AdmCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.AdmCredential AdmCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.AdmCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property AdmCredential As AdmCredential" />
      <MemberSignature Language="F#" Value="member this.AdmCredential : Microsoft.Azure.NotificationHubs.AdmCredential with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.AdmCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="AdmCredential", Order=1014)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.AdmCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または管理者の資格情報を設定します。</summary>
        <value>管理者の資格情報。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApnsCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.ApnsCredential ApnsCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.ApnsCredential ApnsCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.ApnsCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property ApnsCredential As ApnsCredential" />
      <MemberSignature Language="F#" Value="member this.ApnsCredential : Microsoft.Azure.NotificationHubs.ApnsCredential with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.ApnsCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="ApnsCredential", Order=1001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.ApnsCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または APNS 資格情報を設定します。</summary>
        <value>APNS 資格情報です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules Authorization { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authorization As AuthorizationRules" />
      <MemberSignature Language="F#" Value="member this.Authorization : Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>この説明の承認規則を取得します。</summary>
        <value>この説明の承認規則。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaiduCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.BaiduCredential BaiduCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.BaiduCredential BaiduCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.BaiduCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property BaiduCredential As BaiduCredential" />
      <MemberSignature Language="F#" Value="member this.BaiduCredential : Microsoft.Azure.NotificationHubs.BaiduCredential with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.BaiduCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="BaiduCredential", Order=1016)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.BaiduCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Baidu 資格情報を設定します。
            </summary>
        <value>
            Baidu 資格情報です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DailyApiCalls">
      <MemberSignature Language="C#" Value="public long DailyApiCalls { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DailyApiCalls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyApiCalls" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DailyApiCalls As Long" />
      <MemberSignature Language="F#" Value="member this.DailyApiCalls : int64" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyApiCalls" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="DailyApiCalls", Order=1013)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>通知の毎日の API 呼び出しを取得します。</summary>
        <value>通知の毎日の API を呼び出します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DailyMaxActiveDevices">
      <MemberSignature Language="C#" Value="public long DailyMaxActiveDevices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DailyMaxActiveDevices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyMaxActiveDevices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DailyMaxActiveDevices As Long" />
      <MemberSignature Language="F#" Value="member this.DailyMaxActiveDevices : int64" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyMaxActiveDevices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="DailyMaxActiveDevices", Order=1008)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>通知の日単位の最大のアクティブなデバイスを取得します。</summary>
        <value>毎日最大アクティブなデバイスの通知です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DailyMaxActiveRegistrations">
      <MemberSignature Language="C#" Value="public long DailyMaxActiveRegistrations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DailyMaxActiveRegistrations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyMaxActiveRegistrations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DailyMaxActiveRegistrations As Long" />
      <MemberSignature Language="F#" Value="member this.DailyMaxActiveRegistrations : int64" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyMaxActiveRegistrations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="DailyMaxActiveRegistrations", Order=1009)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>通知の最大日単位のアクティブな登録を取得します。</summary>
        <value>1 日最大 active の登録、通知します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DailyOperations">
      <MemberSignature Language="C#" Value="public long DailyOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DailyOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DailyOperations As Long" />
      <MemberSignature Language="F#" Value="member this.DailyOperations : int64" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="DailyOperations", Order=1007)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>説明の日常業務を取得します。</summary>
        <value>説明の日常の運用します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DailyPushes">
      <MemberSignature Language="C#" Value="public long DailyPushes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DailyPushes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyPushes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DailyPushes As Long" />
      <MemberSignature Language="F#" Value="member this.DailyPushes : int64" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyPushes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="DailyPushes", Order=1012)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>通知の毎日のプッシュを取得します。</summary>
        <value>日常的に、通知をプッシュします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultFullSasRuleName">
      <MemberSignature Language="C#" Value="public const string DefaultFullSasRuleName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultFullSasRuleName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.NotificationHubDescription.DefaultFullSasRuleName" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultFullSasRuleName As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultFullSasRuleName : string" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.DefaultFullSasRuleName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>既定の完全 SAS 規則名を指定します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultListenSasRuleName">
      <MemberSignature Language="C#" Value="public const string DefaultListenSasRuleName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultListenSasRuleName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.NotificationHubDescription.DefaultListenSasRuleName" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultListenSasRuleName As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultListenSasRuleName : string" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.DefaultListenSasRuleName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>既定のリッスン SAS 規則名を指定します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GcmCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.GcmCredential GcmCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.GcmCredential GcmCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.GcmCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property GcmCredential As GcmCredential" />
      <MemberSignature Language="F#" Value="member this.GcmCredential : Microsoft.Azure.NotificationHubs.GcmCredential with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.GcmCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="GcmCredential", Order=1005)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.GcmCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または GCM の資格情報を設定します。</summary>
        <value>GCM の資格情報。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAnonymousAccessible">
      <MemberSignature Language="C#" Value="public bool IsAnonymousAccessible { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAnonymousAccessible" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.IsAnonymousAccessible" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsAnonymousAccessible As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAnonymousAccessible : bool" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.IsAnonymousAccessible" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>この説明は、匿名でアクセスできるかどうかを示す値を取得します。</summary>
        <value>説明に匿名でアクセスできる場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDisabled">
      <MemberSignature Language="C#" Value="public bool IsDisabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDisabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.IsDisabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDisabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDisabled : bool with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.IsDisabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.IgnoreDataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この通知ハブが無効になっているかどうかを示す値を取得または設定します。 ときに<see langword="true" />(つまり登録を管理および送信) のすべてのランタイム操作は HTTP ステータス コード 403 を返します<see cref="F:System.Net.HttpStatusCode.Forbidden" />です。
            </summary>
        <value>
          <see langword="true" />この通知ハブは無効にします。 場合、それ以外の場合、<see langword="false" />です。
            </value>
        <remarks>
            マルチ テナント アプリケーションは、複数のパーティ (またはテナント) の代わりに 1 つのモバイル アプリケーションへのプッシュ通知する必要があるアプリケーションです。 テナントごとの 1 つのハブを作成し、名前空間レベルでアプリケーションの資格情報を格納する、テナント間でユーザーの分離を実現するには、この目標を実現するために 1 つのパターンです。 このような場合は、必要になる不正使用を (、結果として得られるその他のテナント用のサービスが低下またはマルチ テナントの余分な料金を回避するために、特定のテナントの通知ハブを無効にするマルチ テナント アプリケーションのアプリケーションの所有者の場合)。
            </remarks>
        <altmember cref="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.InternalStatus" />
        <altmember cref="T:System.Net.HttpStatusCode" />
      </Docs>
    </Member>
    <Member MemberName="MpnsCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.MpnsCredential MpnsCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.MpnsCredential MpnsCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.MpnsCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property MpnsCredential As MpnsCredential" />
      <MemberSignature Language="F#" Value="member this.MpnsCredential : Microsoft.Azure.NotificationHubs.MpnsCredential with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.MpnsCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="MpnsCredential", Order=1006)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.MpnsCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または MPNS の資格情報を設定します。 <see cref="T:Microsoft.Azure.NotificationHubs.MpnsCredential" />いない定義済みの証明書有効 MPNS でインスタンスには、MPNS サポートが認証されていません。</summary>
        <value>MPNS の資格情報。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはこの説明のパスを設定します。</summary>
        <value>この説明のパス。</value>
        <remarks>
              これへの相対パス、<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManager.Address" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrationTtl">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RegistrationTtl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RegistrationTtl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.RegistrationTtl" />
      <MemberSignature Language="VB.NET" Value="Public Property RegistrationTtl As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RegistrationTtl : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.RegistrationTtl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはこの通知ハブのすべての登録の有効期限を設定します。</summary>
        <value>登録 TTL です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAccessPasswords">
      <MemberSignature Language="C#" Value="public void SetAccessPasswords (string fullAccessRuleName, string fullAccessPassword, string listenAccessRuleName, string listenAccessPassword);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetAccessPasswords(string fullAccessRuleName, string fullAccessPassword, string listenAccessRuleName, string listenAccessPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubDescription.SetAccessPasswords(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetAccessPasswords (fullAccessRuleName As String, fullAccessPassword As String, listenAccessRuleName As String, listenAccessPassword As String)" />
      <MemberSignature Language="F#" Value="member this.SetAccessPasswords : string * string * string * string -&gt; unit" Usage="notificationHubDescription.SetAccessPasswords (fullAccessRuleName, fullAccessPassword, listenAccessRuleName, listenAccessPassword)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fullAccessRuleName" Type="System.String" />
        <Parameter Name="fullAccessPassword" Type="System.String" />
        <Parameter Name="listenAccessRuleName" Type="System.String" />
        <Parameter Name="listenAccessPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fullAccessRuleName">フル アクセス規則の名前。</param>
        <param name="fullAccessPassword">フル アクセス パスワード。</param>
        <param name="listenAccessRuleName">リッスン アクセス規則の名前。</param>
        <param name="listenAccessPassword">リッスン アクセス パスワード。</param>
        <summary>アクセスのパスワードを設定します。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            fullAccessRuleName または fullAccessPassword または listenAccessRuleName listenAccessPassword
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SetDefaultAccessPasswords">
      <MemberSignature Language="C#" Value="public void SetDefaultAccessPasswords (string fullAccessPassword, string listenAccessPassword);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetDefaultAccessPasswords(string fullAccessPassword, string listenAccessPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubDescription.SetDefaultAccessPasswords(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetDefaultAccessPasswords (fullAccessPassword As String, listenAccessPassword As String)" />
      <MemberSignature Language="F#" Value="member this.SetDefaultAccessPasswords : string * string -&gt; unit" Usage="notificationHubDescription.SetDefaultAccessPasswords (fullAccessPassword, listenAccessPassword)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fullAccessPassword" Type="System.String" />
        <Parameter Name="listenAccessPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fullAccessPassword">フル アクセス パスワード。</param>
        <param name="listenAccessPassword">リッスン アクセス パスワード。</param>
        <summary>既定のアクセス パスワードを設定します。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            fullAccessPassword または listenAccessPassword
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または説明に関連付けられているユーザーのメタデータを設定します。</summary>
        <value>説明に関連付けられているユーザーのメタデータ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WnsCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.WnsCredential WnsCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.WnsCredential WnsCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.WnsCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property WnsCredential As WnsCredential" />
      <MemberSignature Language="F#" Value="member this.WnsCredential : Microsoft.Azure.NotificationHubs.WnsCredential with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.WnsCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="WnsCredential", Order=1003)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.WnsCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または WNS 資格情報を設定します。</summary>
        <value>WNS 資格情報です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>