<Type Name="ByteSerializable" FullName="System.Fabric.ByteSerializable">
  <TypeSignature Language="C#" Value="public abstract class ByteSerializable : System.Fabric.IByteSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract serializable beforefieldinit ByteSerializable extends System.Object implements class System.Fabric.IByteSerializable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ByteSerializable" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ByteSerializable&#xA;Implements IByteSerializable" />
  <TypeSignature Language="F#" Value="type ByteSerializable = class&#xA;    interface IByteSerializable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IByteSerializable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="364ea-101">シリアル化/逆シリアル化するバイト配列との間にする必要があるクラスは、この基本クラスから継承する必要があります。</span><span class="sxs-lookup"><span data-stu-id="364ea-101">A class that needs to be serialized/deserialized to/from a byte array should inherit from this base class</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ByteSerializable ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ByteSerializable.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FromBytes">
      <MemberSignature Language="C#" Value="public virtual void FromBytes (byte[] data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void FromBytes(unsigned int8[] data) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ByteSerializable.FromBytes(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub FromBytes (data As Byte())" />
      <MemberSignature Language="F#" Value="abstract member FromBytes : byte[] -&gt; unit&#xA;override this.FromBytes : byte[] -&gt; unit" Usage="byteSerializable.FromBytes data" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IByteSerializable.FromBytes(System.Byte[])</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="data"><span data-ttu-id="364ea-102">オブジェクトのバイト配列表現</span><span class="sxs-lookup"><span data-stu-id="364ea-102">Byte array representation of the object</span></span></param>
        <summary>
            <span data-ttu-id="364ea-103">これは、オブジェクトがバイト配列からバックアップを既定の実装</span><span class="sxs-lookup"><span data-stu-id="364ea-103">This is the default implementation to covert an object back from a byte array</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public abstract void Read (System.IO.BinaryReader br);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Read(class System.IO.BinaryReader br) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ByteSerializable.Read(System.IO.BinaryReader)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub Read (br As BinaryReader)" />
      <MemberSignature Language="F#" Value="abstract member Read : System.IO.BinaryReader -&gt; unit" Usage="byteSerializable.Read br" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="br" Type="System.IO.BinaryReader" />
      </Parameters>
      <Docs>
        <param name="br"><span data-ttu-id="364ea-104">BinaryReader オブジェクト</span><span class="sxs-lookup"><span data-stu-id="364ea-104">A BinaryReader object</span></span></param>
        <summary>
            <span data-ttu-id="364ea-105">このメソッドは、バイト配列から変換するように、派生クラスで実装する必要があります。</span><span class="sxs-lookup"><span data-stu-id="364ea-105">This method must be implemented by derived classes so that they can be converted back from a byte array</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToBytes">
      <MemberSignature Language="C#" Value="public virtual byte[] ToBytes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance unsigned int8[] ToBytes() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ByteSerializable.ToBytes" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ToBytes () As Byte()" />
      <MemberSignature Language="F#" Value="abstract member ToBytes : unit -&gt; byte[]&#xA;override this.ToBytes : unit -&gt; byte[]" Usage="byteSerializable.ToBytes " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IByteSerializable.ToBytes</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="364ea-106">これは、オブジェクトをバイト配列に変換するための既定の実装</span><span class="sxs-lookup"><span data-stu-id="364ea-106">This is the default implementation to convert an object into a byte array</span></span>
            </summary>
        <returns><span data-ttu-id="364ea-107">バイト配列</span><span class="sxs-lookup"><span data-stu-id="364ea-107">A byte array</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public abstract void Write (System.IO.BinaryWriter bw);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Write(class System.IO.BinaryWriter bw) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ByteSerializable.Write(System.IO.BinaryWriter)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub Write (bw As BinaryWriter)" />
      <MemberSignature Language="F#" Value="abstract member Write : System.IO.BinaryWriter -&gt; unit" Usage="byteSerializable.Write bw" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bw" Type="System.IO.BinaryWriter" />
      </Parameters>
      <Docs>
        <param name="bw"><span data-ttu-id="364ea-108">BinaryWriter オブジェクト</span><span class="sxs-lookup"><span data-stu-id="364ea-108">A BinaryWriter object</span></span></param>
        <summary>
            <span data-ttu-id="364ea-109">このメソッドはバイト配列に変換するように、派生クラスで実装する必要があります。</span><span class="sxs-lookup"><span data-stu-id="364ea-109">This method must be implemented by derived classes so that they can be converted into a byte array</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>