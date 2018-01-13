<Type Name="CustomHeaderConstants" FullName="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants">
  <TypeSignature Language="C#" Value="public static class CustomHeaderConstants" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CustomHeaderConstants extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants" />
  <TypeSignature Language="VB.NET" Value="Public Class CustomHeaderConstants" />
  <TypeSignature Language="F#" Value="type CustomHeaderConstants = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Ack">
      <MemberSignature Language="C#" Value="public const string Ack;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Ack" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.Ack" />
      <MemberSignature Language="VB.NET" Value="Public Const Ack As String " />
      <MemberSignature Language="F#" Value="val mutable Ack : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.Ack" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            [オプション]デバイスでメッセージの消費量に必要なフィードバックを指定するために使用します。 使用可能な値:"none":「陽性」フィードバックがない: フィードバック メッセージが表示されるメッセージに「負の値」使用された場合: フィードバック メッセージが表示される場合は、デバイスの"full"で完了することがなく、メッセージの有効期限が切れて: 正と負の値の両方
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityId">
      <MemberSignature Language="C#" Value="public const string ActivityId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ActivityId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ActivityId" />
      <MemberSignature Language="VB.NET" Value="Public Const ActivityId As String " />
      <MemberSignature Language="F#" Value="val mutable ActivityId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ActivityId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            x ms アクティビティの id サービス間での REST API で activityID を渡すために使用する値
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public const string ApiVersion;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ApiVersion" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public Const ApiVersion As String " />
      <MemberSignature Language="F#" Value="val mutable ApiVersion : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ApiVersion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            api バージョンは、この要求に使用されるプロトコルのバージョンを指定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientAppId">
      <MemberSignature Language="C#" Value="public const string ClientAppId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ClientAppId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientAppId" />
      <MemberSignature Language="VB.NET" Value="Public Const ClientAppId As String " />
      <MemberSignature Language="F#" Value="val mutable ClientAppId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientAppId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリのクライアント要求を行う JWT の Id に x-ms-クライアント アプリ id のセットです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientAudience">
      <MemberSignature Language="C#" Value="public const string ClientAudience;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ClientAudience" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientAudience" />
      <MemberSignature Language="VB.NET" Value="Public Const ClientAudience As String " />
      <MemberSignature Language="F#" Value="val mutable ClientAudience : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientAudience" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クライアント要求を行う JWT のテナント ID が x ms クライアント ユーザー設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientIpAddress">
      <MemberSignature Language="C#" Value="public const string ClientIpAddress;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ClientIpAddress" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Const ClientIpAddress As String " />
      <MemberSignature Language="F#" Value="val mutable ClientIpAddress : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientIpAddress" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            x ms-クライアントの ip アドレスは、要求で使用されるクライアントの IP アドレスに設定リソース プロバイダーには、クライアントの ip アドレスへのアクセス権がないために必要です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientIssuer">
      <MemberSignature Language="C#" Value="public const string ClientIssuer;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ClientIssuer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientIssuer" />
      <MemberSignature Language="VB.NET" Value="Public Const ClientIssuer As String " />
      <MemberSignature Language="F#" Value="val mutable ClientIssuer : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientIssuer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クライアント要求を行う JWT の発行者が x ms クライアント発行者設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientObjectId">
      <MemberSignature Language="C#" Value="public const string ClientObjectId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ClientObjectId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientObjectId" />
      <MemberSignature Language="VB.NET" Value="Public Const ClientObjectId As String " />
      <MemberSignature Language="F#" Value="val mutable ClientObjectId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientObjectId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            x-ms-クライアント オブジェクト id。 オブジェクト Id、クライアント要求を行う JWT のセットです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public const string ClientRequestId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ClientRequestId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Const ClientRequestId As String " />
      <MemberSignature Language="F#" Value="val mutable ClientRequestId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientRequestId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            中かっこなどの装飾なしの GUID の形式で、x ms-クライアントの要求 id。 呼び出し元が指定した要求 ID (例: クライアント要求 id: 9C4D50EE-2D56-4CD3-8152-34347DC9F2B0)。 指定した要求を識別する、呼び出し元で定義された値。   この値が指定されている場合、値は要求をマップする方法として応答情報に含まれます。 呼び出し元がこのヘッダーは – をリソース プロバイダーが提供する場合*必要があります*の 1 つの要求のトレースを容易にするために、トレースとログが記録されます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientTenantId">
      <MemberSignature Language="C#" Value="public const string ClientTenantId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ClientTenantId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientTenantId" />
      <MemberSignature Language="VB.NET" Value="Public Const ClientTenantId As String " />
      <MemberSignature Language="F#" Value="val mutable ClientTenantId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientTenantId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            x-ms-クライアント テナント id は、クライアント要求を行う JWT のテナント ID に設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public const string CorrelationId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string CorrelationId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Const CorrelationId As String " />
      <MemberSignature Language="F#" Value="val mutable CorrelationId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.CorrelationId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            使用されるメッセージの応答とフィードバックの要求のトレース相関 Id を指定します。リソース プロバイダー*必要があります*Azure 全体でエンド ツー エンド要求を関連付けられるように、これを記録します。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeliveryCount">
      <MemberSignature Language="C#" Value="public const string DeliveryCount;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DeliveryCount" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.DeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public Const DeliveryCount As String " />
      <MemberSignature Language="F#" Value="val mutable DeliveryCount : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.DeliveryCount" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージが以前に配信された回数
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTime">
      <MemberSignature Language="C#" Value="public const string EnqueuedTime;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string EnqueuedTime" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.EnqueuedTime" />
      <MemberSignature Language="VB.NET" Value="Public Const EnqueuedTime As String " />
      <MemberSignature Language="F#" Value="val mutable EnqueuedTime : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.EnqueuedTime" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージがサーバーによって受信された時刻
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiryTime">
      <MemberSignature Language="C#" Value="public const string ExpiryTime;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ExpiryTime" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public Const ExpiryTime As String " />
      <MemberSignature Language="F#" Value="val mutable ExpiryTime : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ExpiryTime" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            [オプション]このメッセージを考慮する場合、時刻の有効期限が切れてください。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpAppPropertyPrefix">
      <MemberSignature Language="C#" Value="public const string HttpAppPropertyPrefix;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string HttpAppPropertyPrefix" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpAppPropertyPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Const HttpAppPropertyPrefix As String " />
      <MemberSignature Language="F#" Value="val mutable HttpAppPropertyPrefix : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpAppPropertyPrefix" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            すべてのアプリケーション プロパティの Http ヘッダーのプレフィックス
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpDevice">
      <MemberSignature Language="C#" Value="public const string HttpDevice;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string HttpDevice" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpDevice" />
      <MemberSignature Language="VB.NET" Value="Public Const HttpDevice As String " />
      <MemberSignature Language="F#" Value="val mutable HttpDevice : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpDevice" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpErrorCodeName">
      <MemberSignature Language="C#" Value="public const string HttpErrorCodeName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string HttpErrorCodeName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpErrorCodeName" />
      <MemberSignature Language="VB.NET" Value="Public Const HttpErrorCodeName As String " />
      <MemberSignature Language="F#" Value="val mutable HttpErrorCodeName : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpErrorCodeName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpIotHub">
      <MemberSignature Language="C#" Value="public const string HttpIotHub;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string HttpIotHub" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpIotHub" />
      <MemberSignature Language="VB.NET" Value="Public Const HttpIotHub As String " />
      <MemberSignature Language="F#" Value="val mutable HttpIotHub : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpIotHub" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpIotHubName">
      <MemberSignature Language="C#" Value="public const string HttpIotHubName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string HttpIotHubName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpIotHubName" />
      <MemberSignature Language="VB.NET" Value="Public Const HttpIotHubName As String " />
      <MemberSignature Language="F#" Value="val mutable HttpIotHubName : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpIotHubName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            内部 HTTP カスタム ヘッダー
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public const string MessageId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string MessageId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Const MessageId As String " />
      <MemberSignature Language="F#" Value="val mutable MessageId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.MessageId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            [方法の 2 つの要求に必要]双方向通信を関連付けるために使用します。 形式: 文字列 (最大 128 文字長) ASCII 7 ビットの英数字文字を使用
            + {'-', ':', '/', '\', '.', '+', '%', '_', '#', '*', '?', '!', '(', ')', ',', '=', '@', ';', '$', '''}. URN の RFC は英数字以外の文字です。
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageLockTimeout">
      <MemberSignature Language="C#" Value="public const string MessageLockTimeout;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string MessageLockTimeout" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.MessageLockTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Const MessageLockTimeout As String " />
      <MemberSignature Language="F#" Value="val mutable MessageLockTimeout : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.MessageLockTimeout" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ロックを放棄し、これにより、メッセージを再度取得する前にメッセージをロックする秒単位の時間
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageLockToken">
      <MemberSignature Language="C#" Value="public const string MessageLockToken;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string MessageLockToken" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.MessageLockToken" />
      <MemberSignature Language="VB.NET" Value="Public Const MessageLockToken As String " />
      <MemberSignature Language="F#" Value="val mutable MessageLockToken : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.MessageLockToken" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得したメッセージのロック トークン 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftAsyncOperationHeaderName">
      <MemberSignature Language="C#" Value="public const string MicrosoftAsyncOperationHeaderName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string MicrosoftAsyncOperationHeaderName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.MicrosoftAsyncOperationHeaderName" />
      <MemberSignature Language="VB.NET" Value="Public Const MicrosoftAsyncOperationHeaderName As String " />
      <MemberSignature Language="F#" Value="val mutable MicrosoftAsyncOperationHeaderName : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.MicrosoftAsyncOperationHeaderName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure AsyncOperation URL に設定する場所実行時間の長い操作の結果をチェックできます。オプションでは、Location ヘッダーだけでなく使用されます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public const string Operation;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Operation" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.Operation" />
      <MemberSignature Language="VB.NET" Value="Public Const Operation As String " />
      <MemberSignature Language="F#" Value="val mutable Operation : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.Operation" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            [オプション]通信パターンでは、メッセージのロールを指定するために使用します。 使用可能な値:"d2c": 製品利用統計情報メッセージ (クラウドへのデバイス)"c2d":"d2creq"の通知: 照会要求"d2cres": 問い合わせ応答"c2dreq":"c2dres"コマンドの要求: コマンドの応答
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrincipalName">
      <MemberSignature Language="C#" Value="public const string PrincipalName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string PrincipalName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.PrincipalName" />
      <MemberSignature Language="VB.NET" Value="Public Const PrincipalName As String " />
      <MemberSignature Language="F#" Value="val mutable PrincipalName : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.PrincipalName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            x ms-クライアントのプリンシパル名が設定されたプリンシパル ID に、クライアント JWT の UPN 要求の発行/です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public const string RequestId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string RequestId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Const RequestId As String " />
      <MemberSignature Language="F#" Value="val mutable RequestId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.RequestId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            x ms-要求 id。 現在の操作では、生成されたサービスの一意の識別子。
            すべてのリソース プロバイダー*必要があります*デバッグを容易にする応答ヘッダーにこの値を返します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnClientRequestId">
      <MemberSignature Language="C#" Value="public const string ReturnClientRequestId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ReturnClientRequestId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ReturnClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Const ReturnClientRequestId As String " />
      <MemberSignature Language="F#" Value="val mutable ReturnClientRequestId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ReturnClientRequestId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            x-ms-return-client-request-id の省略可能な場合は True または false を示し、かどうか、クライアント要求 id を指定する必要があります。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public const string SequenceNumber;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SequenceNumber" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Const SequenceNumber As String " />
      <MemberSignature Language="F#" Value="val mutable SequenceNumber : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.SequenceNumber" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            iot hub sequencenumber メッセージごとに 1 ずつ増加識別子
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public const string To;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string To" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.To" />
      <MemberSignature Language="VB.NET" Value="Public Const To As String " />
      <MemberSignature Language="F#" Value="val mutable To : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.To" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            [必須]メッセージの送信先
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserId">
      <MemberSignature Language="C#" Value="public const string UserId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string UserId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.UserId" />
      <MemberSignature Language="VB.NET" Value="Public Const UserId As String " />
      <MemberSignature Language="F#" Value="val mutable UserId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.UserId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            [フィードバック メッセージで必須]IOT hub によって生成されたメッセージの配信元を指定するために使用します。 使用可能な値:"{ハブ名}/"
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>