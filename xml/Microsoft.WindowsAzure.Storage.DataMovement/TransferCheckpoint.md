<Type Name="TransferCheckpoint" FullName="Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint">
  <TypeSignature Language="C#" Value="public class TransferCheckpoint : System.Runtime.Serialization.ISerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit TransferCheckpoint extends System.Object implements class System.Runtime.Serialization.ISerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferCheckpoint&#xA;Implements ISerializable" />
  <TypeSignature Language="F#" Value="type TransferCheckpoint = class&#xA;    interface ISerializable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Runtime.Serialization.ISerializable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="82371-101">元となる、転送が再開される場合があり、続行、チェックポイントを表します。</span><span class="sxs-lookup"><span data-stu-id="82371-101">Represents a checkpoint from which a transfer may be resumed and continue.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TransferCheckpoint (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="82371-102">シリアル化情報。</span><span class="sxs-lookup"><span data-stu-id="82371-102">Serialization information.</span></span></param>
        <param name="context"><span data-ttu-id="82371-103">ストリーミング コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="82371-103">Streaming context.</span></span></param>
        <summary>
            <span data-ttu-id="82371-104"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.StreamJournal" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="82371-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.StreamJournal" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public virtual void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="abstract member GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit&#xA;override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="transferCheckpoint.GetObjectData (info, context)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Runtime.Serialization.ISerializable.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="82371-105">シリアル化情報オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="82371-105">Serialization info object.</span></span></param>
        <param name="context"><span data-ttu-id="82371-106">ストリーミング コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="82371-106">Streaming context.</span></span></param>
        <summary>
            <span data-ttu-id="82371-107">オブジェクトをシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="82371-107">Serializes the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>