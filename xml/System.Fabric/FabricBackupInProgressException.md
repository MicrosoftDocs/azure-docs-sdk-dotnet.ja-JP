<Type Name="FabricBackupInProgressException" FullName="System.Fabric.FabricBackupInProgressException">
  <TypeSignature Language="C#" Value="public class FabricBackupInProgressException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricBackupInProgressException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricBackupInProgressException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricBackupInProgressException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricBackupInProgressException = class&#xA;    inherit FabricException" />
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
      <para><span data-ttu-id="bd343-101">以前に開始されたバックアップ中にバックアップを開始しようとしてが行われたときにスローされる例外は、進行中です。</span><span class="sxs-lookup"><span data-stu-id="bd343-101">The exception that is thrown when an attempt is made to initiate a backup while a previously initiated backup is still in progress.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricBackupInProgressException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricBackupInProgressException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bd343-102">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricBackupInProgressException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.BackupInProgress" />です。</span><span class="sxs-lookup"><span data-stu-id="bd343-102">Initializes a new instance of <see cref="T:System.Fabric.FabricBackupInProgressException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.BackupInProgress" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricBackupInProgressException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricBackupInProgressException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricBackupInProgressException : string -&gt; System.Fabric.FabricBackupInProgressException" Usage="new System.Fabric.FabricBackupInProgressException message" />
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
          <para><span data-ttu-id="bd343-103">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="bd343-103">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="bd343-104">エラー コードを持つ FabricBackupInProgressException クラスの新しいインスタンスを初期化<see cref="F:System.Fabric.FabricErrorCode.BackupInProgress" />と指定したエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="bd343-104">Initializes a new instance of the FabricBackupInProgressException class with error code <see cref="F:System.Fabric.FabricErrorCode.BackupInProgress" /> and a specified error message.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricBackupInProgressException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricBackupInProgressException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricBackupInProgressException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricBackupInProgressException" Usage="new System.Fabric.FabricBackupInProgressException (info, context)" />
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
        <param name="info">
          <para><span data-ttu-id="bd343-105"><see cref="T:System.Runtime.Serialization.SerializationInfo" />を含むオブジェクトがスローされた例外オブジェクト データをシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="bd343-105">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="bd343-106">転送元または転送先に関するコンテキスト情報を格納する <see cref="T:System.Runtime.Serialization.StreamingContext" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bd343-106">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="bd343-107">Context パラメーターは将来使用するために予約されており、null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="bd343-107">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="bd343-108">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricBackupInProgressException" />コンテキストを指定して、シリアル化されたオブジェクトのデータからのクラスです。</span><span class="sxs-lookup"><span data-stu-id="bd343-108">Initializes a new instance of <see cref="T:System.Fabric.FabricBackupInProgressException" /> class from a serialized object data, with a specified context.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricBackupInProgressException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricBackupInProgressException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricBackupInProgressException : string * Exception -&gt; System.Fabric.FabricBackupInProgressException" Usage="new System.Fabric.FabricBackupInProgressException (message, inner)" />
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
          <para><span data-ttu-id="bd343-109">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="bd343-109">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="bd343-110">内部例外が指定されていない場合、現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="bd343-110">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="bd343-111"><see cref="T:System.Exception" />クラスは、内部例外についての詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="bd343-111">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="bd343-112">指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:System.Fabric.FabricBackupInProgressException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bd343-112">Initializes a new instance of the <see cref="T:System.Fabric.FabricBackupInProgressException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>