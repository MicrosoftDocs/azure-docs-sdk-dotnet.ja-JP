<Type Name="FabricValidationException" FullName="System.Fabric.FabricValidationException">
  <TypeSignature Language="C#" Value="public class FabricValidationException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricValidationException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricValidationException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricValidationException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricValidationException = class&#xA;    inherit FabricException" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e3737-101">テストの容易性の検証の Api によってスローされる例外</span><span class="sxs-lookup"><span data-stu-id="e3737-101">Exception thrown by validation APIs in testability</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricValidationException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricValidationException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e3737-102">FabricValidationException の既定のコンス トラクター</span><span class="sxs-lookup"><span data-stu-id="e3737-102">Default constructor for FabricValidationException</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricValidationException (System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricValidationException.#ctor(System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricValidationException : System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricValidationException" Usage="new System.Fabric.FabricValidationException errorCode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="errorCode"><span data-ttu-id="e3737-103">失敗の FabricErrorCode</span><span class="sxs-lookup"><span data-stu-id="e3737-103">FabricErrorCode for the failure</span></span></param>
        <summary>
            <span data-ttu-id="e3737-104">FabricErrorCode 取得 FabricValidationException のコンス トラクター</span><span class="sxs-lookup"><span data-stu-id="e3737-104">Constructor for FabricValidationException which takes in FabricErrorCode</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricValidationException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricValidationException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricValidationException : string -&gt; System.Fabric.FabricValidationException" Usage="new System.Fabric.FabricValidationException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="e3737-105">エラー メッセージ</span><span class="sxs-lookup"><span data-stu-id="e3737-105">Error message</span></span></param>
        <summary>
            <span data-ttu-id="e3737-106">メッセージにかかる FabricValidationException のコンス トラクター</span><span class="sxs-lookup"><span data-stu-id="e3737-106">Constructor for FabricValidationException which takes in a message</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricValidationException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricValidationException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricValidationException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricValidationException" Usage="new System.Fabric.FabricValidationException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="e3737-107">info</span><span class="sxs-lookup"><span data-stu-id="e3737-107">info</span></span></param>
        <param name="context"><span data-ttu-id="e3737-108">context</span><span class="sxs-lookup"><span data-stu-id="e3737-108">context</span></span></param>
        <summary>
            <span data-ttu-id="e3737-109">FabricValidationException コンス トラクター</span><span class="sxs-lookup"><span data-stu-id="e3737-109">FabricValidationException constructor</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricValidationException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricValidationException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricValidationException : string * Exception -&gt; System.Fabric.FabricValidationException" Usage="new System.Fabric.FabricValidationException (message, inner)" />
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
        <param name="message"><span data-ttu-id="e3737-110">エラー メッセージ</span><span class="sxs-lookup"><span data-stu-id="e3737-110">Error message</span></span></param>
        <param name="inner"><span data-ttu-id="e3737-111">内部例外</span><span class="sxs-lookup"><span data-stu-id="e3737-111">Inner exception</span></span></param>
        <summary>
            <span data-ttu-id="e3737-112">メッセージとに向けて例外を受け取る FabricValidationException のコンス トラクター</span><span class="sxs-lookup"><span data-stu-id="e3737-112">Constructor for FabricValidationException which takes in a message and innner exception</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricValidationException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricValidationException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricValidationException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricValidationException" Usage="new System.Fabric.FabricValidationException (message, errorCode)" />
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
        <param name="message"><span data-ttu-id="e3737-113">エラー メッセージ</span><span class="sxs-lookup"><span data-stu-id="e3737-113">Error message</span></span> </param>
        <param name="errorCode"><span data-ttu-id="e3737-114">ファブリック エラー コード</span><span class="sxs-lookup"><span data-stu-id="e3737-114">Fabric Error code</span></span></param>
        <summary>
            <span data-ttu-id="e3737-115">メッセージにかかる FabricValidationException および FabricErrorCode コンス トラクター</span><span class="sxs-lookup"><span data-stu-id="e3737-115">Constructor for FabricValidationException which takes in a message and FabricErrorCode</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricValidationException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricValidationException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricValidationException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricValidationException" Usage="new System.Fabric.FabricValidationException (info, context, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="e3737-116">info</span><span class="sxs-lookup"><span data-stu-id="e3737-116">info</span></span></param>
        <param name="context"><span data-ttu-id="e3737-117">context</span><span class="sxs-lookup"><span data-stu-id="e3737-117">context</span></span></param>
        <param name="errorCode"><span data-ttu-id="e3737-118">errorCode</span><span class="sxs-lookup"><span data-stu-id="e3737-118">errorCode</span></span></param>
        <summary>
            <span data-ttu-id="e3737-119">FabricValidationException コンス トラクター</span><span class="sxs-lookup"><span data-stu-id="e3737-119">FabricValidationException constructor</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricValidationException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricValidationException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricValidationException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricValidationException" Usage="new System.Fabric.FabricValidationException (message, inner, errorCode)" />
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
        <param name="message"><span data-ttu-id="e3737-120">エラー メッセージ</span><span class="sxs-lookup"><span data-stu-id="e3737-120">Error message</span></span></param>
        <param name="inner"><span data-ttu-id="e3737-121">内部例外</span><span class="sxs-lookup"><span data-stu-id="e3737-121">Inner exception</span></span></param>
        <param name="errorCode"><span data-ttu-id="e3737-122">ファブリック エラー コード</span><span class="sxs-lookup"><span data-stu-id="e3737-122">Fabric error code</span></span></param>
        <summary>
            <span data-ttu-id="e3737-123">メッセージとに向けて例外とファブリック エラー コードは FabricValidationException のコンス トラクター</span><span class="sxs-lookup"><span data-stu-id="e3737-123">Constructor for FabricValidationException which takes in a message and innner exception and fabric error code</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>