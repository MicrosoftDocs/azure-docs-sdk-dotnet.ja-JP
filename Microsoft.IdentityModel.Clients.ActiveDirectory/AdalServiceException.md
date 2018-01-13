<Type Name="AdalServiceException" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException">
  <TypeSignature Language="C#" Value="public class AdalServiceException : Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdalServiceException extends Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException" />
  <TypeSignature Language="VB.NET" Value="Public Class AdalServiceException&#xA;Inherits AdalException" />
  <TypeSignature Language="F#" Value="type AdalServiceException = class&#xA;    inherit AdalException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ユーザーがサービスによって返されるときにスローされる例外の種類では、要求内のユーザーが一致しません。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdalServiceException (string errorCode, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException : string * string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException (errorCode, message)" />
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
        <param name="errorCode">プロトコル エラー コードでは、サービスによって返されるか、クライアントによって生成されます。 これは、コードの例外を処理するために依存することができます。</param>
        <param name="message">例外の原因を説明するエラー メッセージ。</param>
        <summary>
             指定されたエラー コードとエラー メッセージ、例外クラスの新しいインスタンスを初期化します。
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public System.Net.Http.Headers.HttpResponseHeaders Headers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Net.Http.Headers.HttpResponseHeaders Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException.Headers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Headers As HttpResponseHeaders" />
      <MemberSignature Language="F#" Value="member this.Headers : System.Net.Http.Headers.HttpResponseHeaders" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException.Headers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.Http.Headers.HttpResponseHeaders</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エラーを示す応答からヘッダーが含まれています
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceErrorCodes">
      <MemberSignature Language="C#" Value="public string[] ServiceErrorCodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string[] ServiceErrorCodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException.ServiceErrorCodes" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceErrorCodes As String()" />
      <MemberSignature Language="F#" Value="member this.ServiceErrorCodes : string[] with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException.ServiceErrorCodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービスによって返される可能性がある特定のエラー コードを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public int StatusCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusCode As Integer" />
      <MemberSignature Language="F#" Value="member this.StatusCode : int with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="adalServiceException.ToString " />
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