<Type Name="MsalUiRequiredException" FullName="Microsoft.Identity.Client.MsalUiRequiredException">
  <TypeSignature Language="C#" Value="public class MsalUiRequiredException : Microsoft.Identity.Client.MsalException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MsalUiRequiredException extends Microsoft.Identity.Client.MsalException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.MsalUiRequiredException" />
  <TypeSignature Language="VB.NET" Value="Public Class MsalUiRequiredException&#xA;Inherits MsalException" />
  <TypeSignature Language="F#" Value="type MsalUiRequiredException = class&#xA;    inherit MsalException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Identity.Client.MsalException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            例外クラスは、UI 操作が正常に認証に必要な開発者に通知します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalUiRequiredException (string errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalUiRequiredException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalUiRequiredException : string -&gt; Microsoft.Identity.Client.MsalUiRequiredException" Usage="new Microsoft.Identity.Client.MsalUiRequiredException errorCode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="errorCode">
            エラー コードでは、サービスによって返されるか、クライアントによって生成されます。 これは、コードの例外を処理するために依存することができます。
            </param>
        <summary>
            指定されたエラー コードで例外クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalUiRequiredException (string errorCode, string errorMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalUiRequiredException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalUiRequiredException : string * string -&gt; Microsoft.Identity.Client.MsalUiRequiredException" Usage="new Microsoft.Identity.Client.MsalUiRequiredException (errorCode, errorMessage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="errorMessage" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="errorCode">
            エラー コードでは、サービスによって返されるか、クライアントによって生成されます。 これは、コードの例外を処理するために依存することができます。
            </param>
        <param name="errorMessage">例外の原因を説明するエラー メッセージ。</param>
        <summary>
            指定されたエラー コードとエラー メッセージ、例外クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalUiRequiredException (string errorCode, string errorMessage, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalUiRequiredException.#ctor(System.String,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalUiRequiredException : string * string * Exception -&gt; Microsoft.Identity.Client.MsalUiRequiredException" Usage="new Microsoft.Identity.Client.MsalUiRequiredException (errorCode, errorMessage, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="errorMessage" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="errorCode">
            エラー コードでは、サービスによって返されるか、クライアントによって生成されます。 これは、コードの例外を処理するために依存することができます。
            </param>
        <param name="errorMessage">例外の原因を説明するエラー メッセージ。</param>
        <param name="innerException">例外の根本原因を表します。</param>
        <summary>
            指定されたエラー コード、エラー メッセージと内部例外の根本原因を示す例外クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvalidGrantError">
      <MemberSignature Language="C#" Value="public static readonly string InvalidGrantError;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string InvalidGrantError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalUiRequiredException.InvalidGrantError" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly InvalidGrantError As String " />
      <MemberSignature Language="F#" Value=" staticval mutable InvalidGrantError : string" Usage="Microsoft.Identity.Client.MsalUiRequiredException.InvalidGrantError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            標準の OAuth2 プロトコルのエラー コード。 示します、ライブラリに、ユーザーは、新しいトークンを取得するための UI を移動する必要があります。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NoPromptFailedError">
      <MemberSignature Language="C#" Value="public static readonly string NoPromptFailedError;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string NoPromptFailedError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalUiRequiredException.NoPromptFailedError" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly NoPromptFailedError As String " />
      <MemberSignature Language="F#" Value=" staticval mutable NoPromptFailedError : string" Usage="Microsoft.Identity.Client.MsalUiRequiredException.NoPromptFailedError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            2 つの条件のいずれかが発生しました。
            1. PromptBehavior.Never フラグが渡されたとが、ユーザーの介入が必要なために、制約を受け入れられませんでした。
            2. 認証フローが十分な時間枠を短期間で完了するを防ぐをサイレント web 認証中にエラーが発生しました。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NoTokensFoundError">
      <MemberSignature Language="C#" Value="public static readonly string NoTokensFoundError;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string NoTokensFoundError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalUiRequiredException.NoTokensFoundError" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly NoTokensFoundError As String " />
      <MemberSignature Language="F#" Value=" staticval mutable NoTokensFoundError : string" Usage="Microsoft.Identity.Client.MsalUiRequiredException.NoTokensFoundError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            条件に一致するトークンが見つかりませんでした。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenCacheNullError">
      <MemberSignature Language="C#" Value="public static readonly string TokenCacheNullError;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string TokenCacheNullError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalUiRequiredException.TokenCacheNullError" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly TokenCacheNullError As String " />
      <MemberSignature Language="F#" Value=" staticval mutable TokenCacheNullError : string" Usage="Microsoft.Identity.Client.MsalUiRequiredException.TokenCacheNullError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このエラー コードは AcquireTokenSilent 呼び出しから返されたトークンのキャッシュは null 参照が、アプリケーションのコンス トラクターに渡されるときに
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserNullError">
      <MemberSignature Language="C#" Value="public static readonly string UserNullError;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string UserNullError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalUiRequiredException.UserNullError" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly UserNullError As String " />
      <MemberSignature Language="F#" Value=" staticval mutable UserNullError : string" Usage="Microsoft.Identity.Client.MsalUiRequiredException.UserNullError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このエラー コードが返さ AcquireTokenSilent 呼び出しから null ユーザーが AcquireTokenSilent 呼び出しに渡されるとします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>