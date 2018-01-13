<Type Name="FabricInvalidReplicaSelectorException" FullName="System.Fabric.FabricInvalidReplicaSelectorException">
  <TypeSignature Language="C#" Value="public class FabricInvalidReplicaSelectorException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricInvalidReplicaSelectorException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricInvalidReplicaSelectorException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricInvalidReplicaSelectorException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricInvalidReplicaSelectorException = class&#xA;    inherit FabricException" />
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
            <span data-ttu-id="90e7b-101">ReplicaSelector が有効ではない場合にスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="90e7b-101">The exception that is thrown when a ReplicaSelector is invalid.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidReplicaSelectorException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidReplicaSelectorException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="90e7b-102"><see cref="T:System.Fabric.FabricInvalidReplicaSelectorException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="90e7b-102">Initializes a new instance of the <see cref="T:System.Fabric.FabricInvalidReplicaSelectorException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidReplicaSelectorException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidReplicaSelectorException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidReplicaSelectorException : string -&gt; System.Fabric.FabricInvalidReplicaSelectorException" Usage="new System.Fabric.FabricInvalidReplicaSelectorException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="90e7b-103">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="90e7b-103">The error message that explains the reason for the exception.</span></span></param>
        <summary>
            <span data-ttu-id="90e7b-104">指定したエラー メッセージを使用して、<see cref="T:System.Fabric.FabricInvalidReplicaSelectorException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="90e7b-104">Initializes a new instance of the <see cref="T:System.Fabric.FabricInvalidReplicaSelectorException" /> class with a specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidReplicaSelectorException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidReplicaSelectorException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidReplicaSelectorException : string * Exception -&gt; System.Fabric.FabricInvalidReplicaSelectorException" Usage="new System.Fabric.FabricInvalidReplicaSelectorException (message, inner)" />
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
        <param name="message"><span data-ttu-id="90e7b-105">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="90e7b-105">The error message that explains the reason for the exception.</span></span></param>
        <param name="inner"><span data-ttu-id="90e7b-106">内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="90e7b-106">The exception that is the cause of the current exception, or a null reference if no inner exception is specified.</span></span></param>
        <summary>
            <span data-ttu-id="90e7b-107">指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:System.Fabric.FabricInvalidReplicaSelectorException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="90e7b-107">Initializes a new instance of the <see cref="T:System.Fabric.FabricInvalidReplicaSelectorException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidReplicaSelectorException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidReplicaSelectorException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidReplicaSelectorException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricInvalidReplicaSelectorException" Usage="new System.Fabric.FabricInvalidReplicaSelectorException (message, errorCode)" />
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
          <para><span data-ttu-id="90e7b-108">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="90e7b-108">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para>
            <span data-ttu-id="90e7b-109"><see cref="T:System.Fabric.FabricErrorCode" />例外は、周りで折り返されるエラー コードを定義します。</span><span class="sxs-lookup"><span data-stu-id="90e7b-109"><see cref="T:System.Fabric.FabricErrorCode" /> defines the error code that the exception is wrapping around.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="90e7b-110">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidReplicaSelectorException" />メッセージ、エラーのコードを指定します。</span><span class="sxs-lookup"><span data-stu-id="90e7b-110">Initializes a new instance of <see cref="T:System.Fabric.FabricInvalidReplicaSelectorException" /> with specified message and error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>