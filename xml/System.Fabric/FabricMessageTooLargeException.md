<Type Name="FabricMessageTooLargeException" FullName="System.Fabric.FabricMessageTooLargeException">
  <TypeSignature Language="C#" Value="public sealed class FabricMessageTooLargeException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit FabricMessageTooLargeException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricMessageTooLargeException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricMessageTooLargeException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricMessageTooLargeException = class&#xA;    inherit FabricException" />
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
      <para><span data-ttu-id="b470e-101">例外を示すメッセージが大きすぎます。</span><span class="sxs-lookup"><span data-stu-id="b470e-101">The exception that indicates the message is too large.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricMessageTooLargeException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricMessageTooLargeException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="b470e-102">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricMessageTooLargeException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.FabricMessageTooLarge" />です。</span><span class="sxs-lookup"><span data-stu-id="b470e-102">Initializes a new instance of <see cref="T:System.Fabric.FabricMessageTooLargeException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.FabricMessageTooLarge" />.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricMessageTooLargeException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricMessageTooLargeException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricMessageTooLargeException : string -&gt; System.Fabric.FabricMessageTooLargeException" Usage="new System.Fabric.FabricMessageTooLargeException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="b470e-103">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="b470e-103">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="b470e-104">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricMessageTooLargeException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.FabricMessageTooLarge" />と指定したエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="b470e-104">Initializes a new instance of <see cref="T:System.Fabric.FabricMessageTooLargeException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.FabricMessageTooLarge" /> and a specified error message.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricMessageTooLargeException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricMessageTooLargeException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricMessageTooLargeException : string * Exception -&gt; System.Fabric.FabricMessageTooLargeException" Usage="new System.Fabric.FabricMessageTooLargeException (message, inner)" />
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
        <param name="message">
          <para><span data-ttu-id="b470e-105">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="b470e-105">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="b470e-106">内部例外が指定されていない場合、現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="b470e-106">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="b470e-107"><see cref="T:System.Exception" />クラスは、内部例外についての詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="b470e-107">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="b470e-108">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricMessageTooLargeException" />指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="b470e-108">Initializes a new instance of <see cref="T:System.Fabric.FabricMessageTooLargeException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>