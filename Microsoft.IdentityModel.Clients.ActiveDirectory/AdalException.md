<Type Name="AdalException" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException">
  <TypeSignature Language="C#" Value="public class AdalException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdalException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" />
  <TypeSignature Language="VB.NET" Value="Public Class AdalException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type AdalException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public AdalException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public AdalException (string errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException : string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException errorCode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="errorCode">エラー コードでは、サービスによって返されるか、クライアントによって生成されます。 これは、コードの例外を処理するために依存することができます。</param>
        <summary>
             指定されたエラー コードで例外クラスの新しいインスタンスを初期化します。
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdalException (string errorCode, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException : string * Exception -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException (errorCode, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="errorCode">エラー コードでは、サービスによって返されるか、クライアントによって生成されます。 これは、コードの例外を処理するために依存することができます。</param>
        <param name="innerException">内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。 サービスによって返される実際のエラー メッセージが特にがあります。</param>
        <summary>
             指定されたエラー コードとは、この例外の原因となった内部例外への参照を伴う exception クラスの新しいインスタンスを初期化します。
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdalException (string errorCode, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException : string * string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException (errorCode, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="errorCode">エラー コードでは、サービスによって返されるか、クライアントによって生成されます。 これは、コードの例外を処理するために依存することができます。</param>
        <param name="message">例外の原因を説明するエラー メッセージ。</param>
        <summary>
             指定されたエラー コードとエラー メッセージ、例外クラスの新しいインスタンスを初期化します。
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdalException (string errorCode, string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException.#ctor(System.String,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException : string * string * Exception -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException (errorCode, message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="errorCode">エラー コードでは、サービスによって返されるか、クライアントによって生成されます。 これは、コードの例外を処理するために依存することができます。</param>
        <param name="message">例外の原因を説明するエラー メッセージ。</param>
        <param name="innerException">内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。 サービスによって返される実際のエラー メッセージが特にがあります。</param>
        <summary>
             指定されたエラー コード、エラー メッセージおよびこの例外の原因となった内部例外への参照を伴う exception クラスの新しいインスタンスを初期化します。
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public string ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As String" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="adalException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
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