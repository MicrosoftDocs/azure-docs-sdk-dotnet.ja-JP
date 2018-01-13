<Type Name="MsalException" FullName="Microsoft.Identity.Client.MsalException">
  <TypeSignature Language="C#" Value="public class MsalException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MsalException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.MsalException" />
  <TypeSignature Language="VB.NET" Value="Public Class MsalException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type MsalException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            トークンの取得中にエラーが発生したときにスローされる例外の種類。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Exception クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalException (string errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalException : string -&gt; Microsoft.Identity.Client.MsalException" Usage="new Microsoft.Identity.Client.MsalException errorCode" />
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
      <MemberSignature Language="C#" Value="public MsalException (string errorCode, string errorMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalException : string * string -&gt; Microsoft.Identity.Client.MsalException" Usage="new Microsoft.Identity.Client.MsalException (errorCode, errorMessage)" />
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
      <MemberSignature Language="C#" Value="public MsalException (string errorCode, string errorMessage, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalException.#ctor(System.String,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalException : string * string * Exception -&gt; Microsoft.Identity.Client.MsalException" Usage="new Microsoft.Identity.Client.MsalException (errorCode, errorMessage, innerException)" />
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
        <param name="innerException">
            内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。
            </param>
        <summary>
            指定されたエラー コードとは、この例外の原因となった内部例外への参照を伴う exception クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public string ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.MsalException.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As String" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : string" Usage="Microsoft.Identity.Client.MsalException.ErrorCode" />
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
            サービスによって返されるか、クライアントによって生成されたプロトコル エラー コードを取得します。 これは、コードの例外を処理するために依存することができます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="msalException.ToString " />
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
    <Member MemberName="UnknownError">
      <MemberSignature Language="C#" Value="public const string UnknownError;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string UnknownError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalException.UnknownError" />
      <MemberSignature Language="VB.NET" Value="Public Const UnknownError As String " />
      <MemberSignature Language="F#" Value="val mutable UnknownError : string" Usage="Microsoft.Identity.Client.MsalException.UnknownError" />
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
            不明なエラーが発生しました。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>