<Type Name="ServiceException" FullName="Microsoft.ServiceFabric.Services.Communication.ServiceException">
  <TypeSignature Language="C#" Value="public class ServiceException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.ServiceException" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type ServiceException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fded8-101">サービスからの例外に関する情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="fded8-101">Provides an information about an exception from the service.</span></span> <span data-ttu-id="fded8-102">この例外はクライアントに転送するため、サービスから実際の例外をシリアル化することはできません。</span><span class="sxs-lookup"><span data-stu-id="fded8-102">This exception is thrown when the actual exception from the service cannot be serialized for transferring to client.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="fded8-103"><see cref="T:Microsoft.ServiceFabric.Services.Communication.ServiceException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fded8-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Services.Communication.ServiceException" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceException (string actualExceptionType, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string actualExceptionType, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (actualExceptionType As String, message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.ServiceException : string * string -&gt; Microsoft.ServiceFabric.Services.Communication.ServiceException" Usage="new Microsoft.ServiceFabric.Services.Communication.ServiceException (actualExceptionType, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actualExceptionType" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="actualExceptionType"><span data-ttu-id="fded8-104">スローされた例外の ActualExceptionType</span><span class="sxs-lookup"><span data-stu-id="fded8-104">the ActualExceptionType of exception thrown</span></span></param>
        <param name="message"><span data-ttu-id="fded8-105">この例外の原因を説明するエラー メッセージ</span><span class="sxs-lookup"><span data-stu-id="fded8-105">The error message that explains the reason for this exception</span></span>
            </param>
        <summary>
            <span data-ttu-id="fded8-106">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceFabric.Services.Communication.ServiceException" />適切なメッセージを使用します。</span><span class="sxs-lookup"><span data-stu-id="fded8-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Services.Communication.ServiceException" /> class with appropriate message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActualExceptionType">
      <MemberSignature Language="C#" Value="public string ActualExceptionType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActualExceptionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.ServiceException.ActualExceptionType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActualExceptionType As String" />
      <MemberSignature Language="F#" Value="member this.ActualExceptionType : string" Usage="Microsoft.ServiceFabric.Services.Communication.ServiceException.ActualExceptionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fded8-107">ActualExceptionType がスローされた例外の実際の型を取得します。</span><span class="sxs-lookup"><span data-stu-id="fded8-107">Gets the ActualExceptionType is the type of actual exception thrown.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>