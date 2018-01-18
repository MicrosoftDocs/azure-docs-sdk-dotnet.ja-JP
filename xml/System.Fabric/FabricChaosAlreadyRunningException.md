<Type Name="FabricChaosAlreadyRunningException" FullName="System.Fabric.FabricChaosAlreadyRunningException">
  <TypeSignature Language="C#" Value="public class FabricChaosAlreadyRunningException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricChaosAlreadyRunningException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricChaosAlreadyRunningException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricChaosAlreadyRunningException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricChaosAlreadyRunningException = class&#xA;    inherit FabricException" />
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
      <para><span data-ttu-id="cc20d-101">クラスターでサービスが既に実行されているときに、Service Fabric の組み込みの複雑さテスト サービスの新しいインスタンスを作成しようとした場合にスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="cc20d-101">The exception that is thrown when there is an attempt to create a new instance of Service Fabric's built-in Chaos Test service, while the service is already running in the cluster.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricChaosAlreadyRunningException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricChaosAlreadyRunningException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cc20d-102">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricChaosAlreadyRunningException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.ChaosAlreadyRunning" />です。</span><span class="sxs-lookup"><span data-stu-id="cc20d-102">Initializes a new instance of <see cref="T:System.Fabric.FabricChaosAlreadyRunningException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.ChaosAlreadyRunning" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricChaosAlreadyRunningException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricChaosAlreadyRunningException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricChaosAlreadyRunningException : string -&gt; System.Fabric.FabricChaosAlreadyRunningException" Usage="new System.Fabric.FabricChaosAlreadyRunningException message" />
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
          <para><span data-ttu-id="cc20d-103">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="cc20d-103">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="cc20d-104">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricChaosAlreadyRunningException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.ChaosAlreadyRunning" />と指定したエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="cc20d-104">Initializes a new instance of <see cref="T:System.Fabric.FabricChaosAlreadyRunningException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.ChaosAlreadyRunning" /> and a specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricChaosAlreadyRunningException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricChaosAlreadyRunningException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricChaosAlreadyRunningException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricChaosAlreadyRunningException" Usage="new System.Fabric.FabricChaosAlreadyRunningException (info, context)" />
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
          <para><span data-ttu-id="cc20d-105"><see cref="T:System.Runtime.Serialization.SerializationInfo" />を含むオブジェクトがスローされた例外オブジェクト データをシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="cc20d-105">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="cc20d-106">転送元または転送先に関するコンテキスト情報を格納する <see cref="T:System.Runtime.Serialization.StreamingContext" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="cc20d-106">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="cc20d-107">Context パラメーターは将来使用するために予約されており、null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="cc20d-107">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="cc20d-108">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricChaosAlreadyRunningException" />コンテキストを指定して、シリアル化されたオブジェクトのデータからのクラスです。</span><span class="sxs-lookup"><span data-stu-id="cc20d-108">Initializes a new instance of <see cref="T:System.Fabric.FabricChaosAlreadyRunningException" /> class from a serialized object data, with a specified context.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricChaosAlreadyRunningException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricChaosAlreadyRunningException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricChaosAlreadyRunningException : string * Exception -&gt; System.Fabric.FabricChaosAlreadyRunningException" Usage="new System.Fabric.FabricChaosAlreadyRunningException (message, inner)" />
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
          <para><span data-ttu-id="cc20d-109">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="cc20d-109">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="cc20d-110">内部例外が指定されていない場合、現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="cc20d-110">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="cc20d-111"><see cref="T:System.Exception" />クラスは、内部例外についての詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="cc20d-111">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="cc20d-112">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricChaosAlreadyRunningException" />指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="cc20d-112">Initializes a new instance of <see cref="T:System.Fabric.FabricChaosAlreadyRunningException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>