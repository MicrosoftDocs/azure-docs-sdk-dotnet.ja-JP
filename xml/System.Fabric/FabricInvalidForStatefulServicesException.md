<Type Name="FabricInvalidForStatefulServicesException" FullName="System.Fabric.FabricInvalidForStatefulServicesException">
  <TypeSignature Language="C#" Value="public class FabricInvalidForStatefulServicesException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricInvalidForStatefulServicesException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricInvalidForStatefulServicesException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricInvalidForStatefulServicesException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricInvalidForStatefulServicesException = class&#xA;    inherit FabricException" />
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
            <span data-ttu-id="d39e5-101">操作はステートレスなサービスの場合にスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="d39e5-101">The exception that is thrown when an operation is only valid for stateless services.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidForStatefulServicesException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidForStatefulServicesException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d39e5-102"><see cref="T:System.Fabric.FabricInvalidForStatefulServicesException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d39e5-102">Initializes a new instance of the <see cref="T:System.Fabric.FabricInvalidForStatefulServicesException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidForStatefulServicesException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidForStatefulServicesException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidForStatefulServicesException : string -&gt; System.Fabric.FabricInvalidForStatefulServicesException" Usage="new System.Fabric.FabricInvalidForStatefulServicesException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="d39e5-103">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="d39e5-103">The error message that explains the reason for the exception.</span></span></param>
        <summary>
            <span data-ttu-id="d39e5-104">指定したエラー メッセージを使用して、<see cref="T:System.Fabric.FabricInvalidForStatefulServicesException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d39e5-104">Initializes a new instance of the <see cref="T:System.Fabric.FabricInvalidForStatefulServicesException" /> class with a specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidForStatefulServicesException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidForStatefulServicesException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidForStatefulServicesException : string * Exception -&gt; System.Fabric.FabricInvalidForStatefulServicesException" Usage="new System.Fabric.FabricInvalidForStatefulServicesException (message, inner)" />
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
        <param name="message"><span data-ttu-id="d39e5-105">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="d39e5-105">The error message that explains the reason for the exception.</span></span></param>
        <param name="inner"><span data-ttu-id="d39e5-106">内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="d39e5-106">The exception that is the cause of the current exception, or a null reference if no inner exception is specified.</span></span></param>
        <summary>
            <span data-ttu-id="d39e5-107">指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:System.Fabric.FabricInvalidForStatefulServicesException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d39e5-107">Initializes a new instance of the <see cref="T:System.Fabric.FabricInvalidForStatefulServicesException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidForStatefulServicesException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidForStatefulServicesException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidForStatefulServicesException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricInvalidForStatefulServicesException" Usage="new System.Fabric.FabricInvalidForStatefulServicesException (message, errorCode)" />
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
          <para><span data-ttu-id="d39e5-108">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="d39e5-108">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para>
            <span data-ttu-id="d39e5-109"><see cref="T:System.Fabric.FabricErrorCode" />例外は、周りで折り返されるエラー コードを定義します。</span><span class="sxs-lookup"><span data-stu-id="d39e5-109"><see cref="T:System.Fabric.FabricErrorCode" /> defines the error code that the exception is wrapping around.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="d39e5-110">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidForStatefulServicesException" />メッセージ、エラーのコードを指定します。</span><span class="sxs-lookup"><span data-stu-id="d39e5-110">Initializes a new instance of <see cref="T:System.Fabric.FabricInvalidForStatefulServicesException" /> with specified message and error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidForStatefulServicesException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidForStatefulServicesException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidForStatefulServicesException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricInvalidForStatefulServicesException" Usage="new System.Fabric.FabricInvalidForStatefulServicesException (message, inner, errorCode)" />
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
        <param name="message"><span data-ttu-id="d39e5-111">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="d39e5-111">The error message that explains the reason for the exception.</span></span></param>
        <param name="inner"><span data-ttu-id="d39e5-112">内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="d39e5-112">The exception that is the cause of the current exception, or a null reference if no inner exception is specified.</span></span></param>
        <param name="errorCode">
          <para>
            <span data-ttu-id="d39e5-113"><see cref="T:System.Fabric.FabricErrorCode" />例外は、周りで折り返されるエラー コードを定義します。</span><span class="sxs-lookup"><span data-stu-id="d39e5-113"><see cref="T:System.Fabric.FabricErrorCode" /> defines the error code that the exception is wrapping around.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="d39e5-114">指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:System.Fabric.FabricInvalidForStatefulServicesException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d39e5-114">Initializes a new instance of the <see cref="T:System.Fabric.FabricInvalidForStatefulServicesException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>