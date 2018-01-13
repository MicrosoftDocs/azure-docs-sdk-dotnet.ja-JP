<Type Name="FabricRestoreSafeCheckFailedException" FullName="System.Fabric.FabricRestoreSafeCheckFailedException">
  <TypeSignature Language="C#" Value="public class FabricRestoreSafeCheckFailedException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricRestoreSafeCheckFailedException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricRestoreSafeCheckFailedException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricRestoreSafeCheckFailedException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricRestoreSafeCheckFailedException = class&#xA;    inherit FabricException" />
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
            <span data-ttu-id="0bc96-101">バックアップが古すぎるため、復元のために使用する場合にスローされる例外</span><span class="sxs-lookup"><span data-stu-id="0bc96-101">The exception that is thrown when Backup is too old to be used for restore</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricRestoreSafeCheckFailedException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRestoreSafeCheckFailedException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0bc96-102"><see cref="T:System.Fabric.FabricRestoreSafeCheckFailedException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0bc96-102">Initializes a new instance of the <see cref="T:System.Fabric.FabricRestoreSafeCheckFailedException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricRestoreSafeCheckFailedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRestoreSafeCheckFailedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricRestoreSafeCheckFailedException : string -&gt; System.Fabric.FabricRestoreSafeCheckFailedException" Usage="new System.Fabric.FabricRestoreSafeCheckFailedException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="0bc96-103">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="0bc96-103">The error message that explains the reason for the exception.</span></span></param>
        <summary>
            <span data-ttu-id="0bc96-104">指定したエラー メッセージを使用して、<see cref="T:System.Fabric.FabricRestoreSafeCheckFailedException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0bc96-104">Initializes a new instance of the <see cref="T:System.Fabric.FabricRestoreSafeCheckFailedException" /> class with a specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricRestoreSafeCheckFailedException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRestoreSafeCheckFailedException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricRestoreSafeCheckFailedException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricRestoreSafeCheckFailedException" Usage="new System.Fabric.FabricRestoreSafeCheckFailedException (info, context)" />
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
        <param name="info"><span data-ttu-id="0bc96-105">スローされている例外に関するシリアル化済みオブジェクト データを保持している <see cref="T:System.Runtime.Serialization.SerializationInfo" />。</span><span class="sxs-lookup"><span data-stu-id="0bc96-105">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> that holds the serialized object data about the exception being thrown.</span></span> </param>
        <param name="context"><span data-ttu-id="0bc96-106">転送元または転送先についてのコンテキスト情報を含む <see cref="T:System.Runtime.Serialization.StreamingContext" /> です。</span><span class="sxs-lookup"><span data-stu-id="0bc96-106">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> that contains contextual information about the source or destination.</span></span></param>
        <summary>
            <span data-ttu-id="0bc96-107">シリアル化したデータを使用して、<see cref="T:System.Fabric.FabricRestoreSafeCheckFailedException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0bc96-107">Initializes a new instance of the <see cref="T:System.Fabric.FabricRestoreSafeCheckFailedException" /> class with serialized data.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricRestoreSafeCheckFailedException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRestoreSafeCheckFailedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricRestoreSafeCheckFailedException : string * Exception -&gt; System.Fabric.FabricRestoreSafeCheckFailedException" Usage="new System.Fabric.FabricRestoreSafeCheckFailedException (message, inner)" />
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
        <param name="message"><span data-ttu-id="0bc96-108">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="0bc96-108">The error message that explains the reason for the exception.</span></span></param>
        <param name="inner"><span data-ttu-id="0bc96-109">内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="0bc96-109">The exception that is the cause of the current exception, or a null reference if no inner exception is specified.</span></span></param>
        <summary>
            <span data-ttu-id="0bc96-110">指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:System.Fabric.FabricRestoreSafeCheckFailedException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0bc96-110">Initializes a new instance of the <see cref="T:System.Fabric.FabricRestoreSafeCheckFailedException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>