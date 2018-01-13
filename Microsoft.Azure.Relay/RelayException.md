<Type Name="RelayException" FullName="Microsoft.Azure.Relay.RelayException">
  <TypeSignature Language="C#" Value="public class RelayException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit RelayException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.RelayException" />
  <TypeSignature Language="VB.NET" Value="Public Class RelayException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type RelayException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ca19f-101">リレー エラーに対してスローされる例外を表します。</span><span class="sxs-lookup"><span data-stu-id="ca19f-101">Represents exceptions thrown for for relay errors.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ca19f-102">
                      <see cref="T:Microsoft.Azure.Relay.RelayException" /> クラスの新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="ca19f-102">Creates a new instance of the <see cref="T:Microsoft.Azure.Relay.RelayException" /> class.</span></span>
</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.RelayException : string -&gt; Microsoft.Azure.Relay.RelayException" Usage="new Microsoft.Azure.Relay.RelayException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="ca19f-103">エラーを説明するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="ca19f-103">The message that describes the error.</span></span></param>
        <summary>
            <span data-ttu-id="ca19f-104">新しいインスタンスを作成、<see cref="T:Microsoft.Azure.Relay.RelayException" />指定したエラー メッセージを使用します。</span><span class="sxs-lookup"><span data-stu-id="ca19f-104">Creates a new instance of the <see cref="T:Microsoft.Azure.Relay.RelayException" /> class with a specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected RelayException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.RelayException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Relay.RelayException" Usage="new Microsoft.Azure.Relay.RelayException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="ca19f-105">スローされている例外に関するシリアル化済みオブジェクト データを保持している <see cref="T:System.Runtime.Serialization.SerializationInfo" />。</span><span class="sxs-lookup"><span data-stu-id="ca19f-105">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> that holds the serialized object data about the exception being thrown.</span></span> </param>
        <param name="context"><span data-ttu-id="ca19f-106">転送元または転送先についてのコンテキスト情報を含む <see cref="T:System.Runtime.Serialization.StreamingContext" /> です。</span><span class="sxs-lookup"><span data-stu-id="ca19f-106">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> that contains contextual information about the source or destination.</span></span> </param>
        <summary>
            <span data-ttu-id="ca19f-107">新しいインスタンスを作成、<see cref="T:Microsoft.Azure.Relay.RelayException" />シリアル化されたデータを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="ca19f-107">Creates a new instance of the <see cref="T:Microsoft.Azure.Relay.RelayException" /> class with serialized data.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.RelayException : string * Exception -&gt; Microsoft.Azure.Relay.RelayException" Usage="new Microsoft.Azure.Relay.RelayException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="ca19f-108">エラーを説明するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="ca19f-108">The message that describes the error.</span></span></param>
        <param name="innerException"><span data-ttu-id="ca19f-109">現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="ca19f-109">The exception that is the cause of the current exception.</span></span></param>
        <summary>
            <span data-ttu-id="ca19f-110">新しいインスタンスを作成、<see cref="T:Microsoft.Azure.Relay.RelayException" />指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="ca19f-110">Creates a new instance of the <see cref="T:Microsoft.Azure.Relay.RelayException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsTransient">
      <MemberSignature Language="C#" Value="public bool IsTransient { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsTransient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayException.IsTransient" />
      <MemberSignature Language="VB.NET" Value="Public Property IsTransient As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsTransient : bool with get, set" Usage="Microsoft.Azure.Relay.RelayException.IsTransient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ca19f-111">例外は一時的なものかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="ca19f-111">Gets a value indicating whether the exception is transient.</span></span> <span data-ttu-id="ca19f-112">操作を再試行するかどうかを決定するには、このプロパティを確認します。</span><span class="sxs-lookup"><span data-stu-id="ca19f-112">Check this property to determine if the operation should be retried.</span></span></summary>
        <value><span data-ttu-id="ca19f-113">例外が; 一時的な場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="ca19f-113">true if the exception is transient; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>