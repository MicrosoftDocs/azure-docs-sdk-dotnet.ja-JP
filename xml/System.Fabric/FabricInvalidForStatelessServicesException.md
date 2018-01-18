<Type Name="FabricInvalidForStatelessServicesException" FullName="System.Fabric.FabricInvalidForStatelessServicesException">
  <TypeSignature Language="C#" Value="public class FabricInvalidForStatelessServicesException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricInvalidForStatelessServicesException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricInvalidForStatelessServicesException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricInvalidForStatelessServicesException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricInvalidForStatelessServicesException = class&#xA;    inherit FabricException" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.MaintainabilityRules", "SA1402:FileMayOnlyContainASingleClass", Justification="Exception")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3f235-101">操作はステートフル サービスの場合にスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="3f235-101">The exception that is thrown when an operation is only valid for stateful services.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidForStatelessServicesException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidForStatelessServicesException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3f235-102"><see cref="T:System.Fabric.FabricInvalidForStatelessServicesException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3f235-102">Initializes a new instance of the <see cref="T:System.Fabric.FabricInvalidForStatelessServicesException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidForStatelessServicesException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidForStatelessServicesException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidForStatelessServicesException : string -&gt; System.Fabric.FabricInvalidForStatelessServicesException" Usage="new System.Fabric.FabricInvalidForStatelessServicesException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="3f235-103">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="3f235-103">The error message that explains the reason for the exception.</span></span></param>
        <summary>
            <span data-ttu-id="3f235-104">指定したエラー メッセージを使用して、<see cref="T:System.Fabric.FabricInvalidForStatelessServicesException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3f235-104">Initializes a new instance of the <see cref="T:System.Fabric.FabricInvalidForStatelessServicesException" /> class with a specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidForStatelessServicesException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidForStatelessServicesException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidForStatelessServicesException : string * Exception -&gt; System.Fabric.FabricInvalidForStatelessServicesException" Usage="new System.Fabric.FabricInvalidForStatelessServicesException (message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="3f235-105">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="3f235-105">The error message that explains the reason for the exception.</span></span></param>
        <param name="inner"><span data-ttu-id="3f235-106">内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="3f235-106">The exception that is the cause of the current exception, or a null reference if no inner exception is specified.</span></span></param>
        <summary>
            <span data-ttu-id="3f235-107">指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:System.Fabric.FabricInvalidForStatelessServicesException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3f235-107">Initializes a new instance of the <see cref="T:System.Fabric.FabricInvalidForStatelessServicesException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidForStatelessServicesException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidForStatelessServicesException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidForStatelessServicesException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricInvalidForStatelessServicesException" Usage="new System.Fabric.FabricInvalidForStatelessServicesException (message, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="3f235-108">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="3f235-108">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para>
            <span data-ttu-id="3f235-109"><see cref="T:System.Fabric.FabricErrorCode" />例外は、周りで折り返されるエラー コードを定義します。</span><span class="sxs-lookup"><span data-stu-id="3f235-109"><see cref="T:System.Fabric.FabricErrorCode" /> defines the error code that the exception is wrapping around.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3f235-110">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidForStatelessServicesException" />メッセージ、エラーのコードを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f235-110">Initializes a new instance of <see cref="T:System.Fabric.FabricInvalidForStatelessServicesException" /> with specified message and error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidForStatelessServicesException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidForStatelessServicesException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidForStatelessServicesException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricInvalidForStatelessServicesException" Usage="new System.Fabric.FabricInvalidForStatelessServicesException (message, inner, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="3f235-111">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="3f235-111">The error message that explains the reason for the exception.</span></span></param>
        <param name="inner"><span data-ttu-id="3f235-112">内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="3f235-112">The exception that is the cause of the current exception, or a null reference if no inner exception is specified.</span></span></param>
        <param name="errorCode">
          <para>
            <span data-ttu-id="3f235-113"><see cref="T:System.Fabric.FabricErrorCode" />例外は、周りで折り返されるエラー コードを定義します。</span><span class="sxs-lookup"><span data-stu-id="3f235-113"><see cref="T:System.Fabric.FabricErrorCode" /> defines the error code that the exception is wrapping around.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="3f235-114">指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:System.Fabric.FabricInvalidForStatelessServicesException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3f235-114">Initializes a new instance of the <see cref="T:System.Fabric.FabricInvalidForStatelessServicesException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>