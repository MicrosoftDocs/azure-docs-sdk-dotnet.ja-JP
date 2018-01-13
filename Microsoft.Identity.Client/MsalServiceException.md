<Type Name="MsalServiceException" FullName="Microsoft.Identity.Client.MsalServiceException">
  <TypeSignature Language="C#" Value="public class MsalServiceException : Microsoft.Identity.Client.MsalException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MsalServiceException extends Microsoft.Identity.Client.MsalException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.MsalServiceException" />
  <TypeSignature Language="VB.NET" Value="Public Class MsalServiceException&#xA;Inherits MsalException" />
  <TypeSignature Language="F#" Value="type MsalServiceException = class&#xA;    inherit MsalException" />
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
            サービスが返されるときにスローされる例外の種類とエラー応答またはその他のネットワーク エラーが発生します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalServiceException (string errorCode, string errorMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalServiceException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalServiceException : string * string -&gt; Microsoft.Identity.Client.MsalServiceException" Usage="new Microsoft.Identity.Client.MsalServiceException (errorCode, errorMessage)" />
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
            プロトコル エラー コードでは、サービスによって返されるか、クライアントによって生成されます。 これは、コードの例外を処理するために依存することができます。
            </param>
        <param name="errorMessage">例外の原因を説明するエラー メッセージ。</param>
        <summary>
            指定されたエラー コード、エラー メッセージおよびこの例外の原因となった内部例外への参照を伴う exception クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalServiceException (string errorCode, string errorMessage, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalServiceException.#ctor(System.String,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalServiceException : string * string * Exception -&gt; Microsoft.Identity.Client.MsalServiceException" Usage="new Microsoft.Identity.Client.MsalServiceException (errorCode, errorMessage, innerException)" />
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
            プロトコル エラー コードでは、サービスによって返されるか、クライアントによって生成されます。 これは、コードの例外を処理するために依存することができます。
            </param>
        <param name="errorMessage">例外の原因を説明するエラー メッセージ。</param>
        <param name="innerException">
            内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。
            </param>
        <summary>
            指定されたエラー コード、エラー メッセージおよびこの例外の原因となった内部例外への参照を伴う exception クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalServiceException (string errorCode, string errorMessage, int statusCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage, int32 statusCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalServiceException.#ctor(System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String, statusCode As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalServiceException : string * string * int -&gt; Microsoft.Identity.Client.MsalServiceException" Usage="new Microsoft.Identity.Client.MsalServiceException (errorCode, errorMessage, statusCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="errorMessage" Type="System.String" />
        <Parameter Name="statusCode" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="errorCode">
            プロトコル エラー コードでは、サービスによって返されるか、クライアントによって生成されます。 これは、コードの例外を処理するために依存することができます。
            </param>
        <param name="errorMessage">例外の原因を説明するエラー メッセージ。</param>
        <param name="statusCode">サービスから受信した resposne のステータス コード。</param>
        <summary>
            指定されたエラー コード、エラー メッセージおよびこの例外の原因となった内部例外への参照を伴う exception クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalServiceException (string errorCode, string errorMessage, int statusCode, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage, int32 statusCode, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalServiceException.#ctor(System.String,System.String,System.Int32,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String, statusCode As Integer, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalServiceException : string * string * int * Exception -&gt; Microsoft.Identity.Client.MsalServiceException" Usage="new Microsoft.Identity.Client.MsalServiceException (errorCode, errorMessage, statusCode, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="errorMessage" Type="System.String" />
        <Parameter Name="statusCode" Type="System.Int32" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="errorCode">
            プロトコル エラー コードでは、サービスによって返されるか、クライアントによって生成されます。 これは、コードの例外を処理するために依存することができます。
            </param>
        <param name="errorMessage">例外の原因を説明するエラー メッセージ。</param>
        <param name="statusCode">サービスから受信した resposne のステータス コード。</param>
        <param name="innerException">
            内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。
            </param>
        <summary>
            指定されたエラー コード、エラー メッセージおよびこの例外の原因となった内部例外への参照を伴う exception クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalServiceException (string errorCode, string errorMessage, int statusCode, string claims, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage, int32 statusCode, string claims, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalServiceException.#ctor(System.String,System.String,System.Int32,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String, statusCode As Integer, claims As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalServiceException : string * string * int * string * Exception -&gt; Microsoft.Identity.Client.MsalServiceException" Usage="new Microsoft.Identity.Client.MsalServiceException (errorCode, errorMessage, statusCode, claims, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="errorMessage" Type="System.String" />
        <Parameter Name="statusCode" Type="System.Int32" />
        <Parameter Name="claims" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="errorCode">
            プロトコル エラー コードでは、サービスによって返されるか、クライアントによって生成されます。 これは、コードの例外を処理するために依存することができます。
            </param>
        <param name="errorMessage">例外の原因を説明するエラー メッセージ。</param>
        <param name="statusCode">要求のステータス コード。</param>
        <param name="claims">クレームは、サービスから返されるバックアップをチャレンジします。</param>
        <param name="innerException">
            内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。
            </param>
        <summary>
            指定されたエラー コード、エラー メッセージおよびこの例外の原因となった内部例外への参照を伴う exception クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Claims">
      <MemberSignature Language="C#" Value="public string Claims { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Claims" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.MsalServiceException.Claims" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Claims As String" />
      <MemberSignature Language="F#" Value="member this.Claims : string" Usage="Microsoft.Identity.Client.MsalServiceException.Claims" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestTimeout">
      <MemberSignature Language="C#" Value="public const string RequestTimeout;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string RequestTimeout" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalServiceException.RequestTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Const RequestTimeout As String " />
      <MemberSignature Language="F#" Value="val mutable RequestTimeout : string" Usage="Microsoft.Identity.Client.MsalServiceException.RequestTimeout" />
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
            Http 要求がタイムアウトしました。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseBody">
      <MemberSignature Language="C#" Value="public string ResponseBody { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResponseBody" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.MsalServiceException.ResponseBody" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseBody As String" />
      <MemberSignature Language="F#" Value="member this.ResponseBody : string" Usage="Microsoft.Identity.Client.MsalServiceException.ResponseBody" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サーバーから受け取った未加工の応答本文です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceNotAvailable">
      <MemberSignature Language="C#" Value="public const string ServiceNotAvailable;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ServiceNotAvailable" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalServiceException.ServiceNotAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Const ServiceNotAvailable As String " />
      <MemberSignature Language="F#" Value="val mutable ServiceNotAvailable : string" Usage="Microsoft.Identity.Client.MsalServiceException.ServiceNotAvailable" />
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
            サービスを利用し、500 ~ 599 の範囲内の HTTP エラー コードが返されました。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public int StatusCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.MsalServiceException.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusCode As Integer" />
      <MemberSignature Language="F#" Value="member this.StatusCode : int" Usage="Microsoft.Identity.Client.MsalServiceException.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Http 層から返されたステータス コードを取得します。 この状態コードは内部 HttpRequestException 応答で、いずれかの HttpStatusCode またはブラウザーで NavigateError イベントのステータス コード ベースのフロー (を参照してください http://msdn.microsoft.com/en-us/library/bb268233 (v=vs.85).aspx)。
            再試行ロジックやエラーの調査を実装するなどの目的は、このコードを使用することができます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalServiceException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="msalServiceException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在の例外の文字列形式を作成して返します。
            </summary>
        <returns>現在の例外の文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>