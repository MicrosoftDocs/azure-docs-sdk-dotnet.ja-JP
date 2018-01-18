<Type Name="AdalUserMismatchException" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException">
  <TypeSignature Language="C#" Value="public class AdalUserMismatchException : Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdalUserMismatchException extends Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException" />
  <TypeSignature Language="VB.NET" Value="Public Class AdalUserMismatchException&#xA;Inherits AdalException" />
  <TypeSignature Language="F#" Value="type AdalUserMismatchException = class&#xA;    inherit AdalException" />
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
            <span data-ttu-id="ef4fc-101">ユーザーがサービスによって返されるときにスローされる例外の種類では、要求内のユーザーが一致しません。</span><span class="sxs-lookup"><span data-stu-id="ef4fc-101">The exception type thrown when user returned by service does not match user in the request.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdalUserMismatchException (string requestedUser, string returnedUser);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string requestedUser, string returnedUser) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (requestedUser As String, returnedUser As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException : string * string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException (requestedUser, returnedUser)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="requestedUser" Type="System.String" />
        <Parameter Name="returnedUser" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="requestedUser">To be added.</param>
        <param name="returnedUser">To be added.</param>
        <summary>
             <span data-ttu-id="ef4fc-102">Exception クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ef4fc-102">Initializes a new instance of the exception class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedUser">
      <MemberSignature Language="C#" Value="public string RequestedUser { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedUser" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException.RequestedUser" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedUser As String" />
      <MemberSignature Language="F#" Value="member this.RequestedUser : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException.RequestedUser" />
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
            <span data-ttu-id="ef4fc-103">サービスから要求されたユーザーを取得します。</span><span class="sxs-lookup"><span data-stu-id="ef4fc-103">Gets the user requested from service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnedUser">
      <MemberSignature Language="C#" Value="public string ReturnedUser { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReturnedUser" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException.ReturnedUser" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReturnedUser As String" />
      <MemberSignature Language="F#" Value="member this.ReturnedUser : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException.ReturnedUser" />
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
            <span data-ttu-id="ef4fc-104">サービスによって返されるユーザーを取得します。</span><span class="sxs-lookup"><span data-stu-id="ef4fc-104">Gets the user returned by service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="adalUserMismatchException.ToString " />
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
            <span data-ttu-id="ef4fc-105">現在の例外の文字列形式を作成して返します。</span><span class="sxs-lookup"><span data-stu-id="ef4fc-105">Creates and returns a string representation of the current exception.</span></span>
            </summary>
        <returns><span data-ttu-id="ef4fc-106">現在の例外の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="ef4fc-106">A string representation of the current exception.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>