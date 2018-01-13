<Type Name="CheckSequencePropertyOperation" FullName="System.Fabric.CheckSequencePropertyOperation">
  <TypeSignature Language="C#" Value="public sealed class CheckSequencePropertyOperation : System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CheckSequencePropertyOperation extends System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.CheckSequencePropertyOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CheckSequencePropertyOperation&#xA;Inherits PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type CheckSequencePropertyOperation = class&#xA;    inherit PropertyBatchOperation" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.PropertyBatchOperation</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="23529-101">比較、<see cref="P:System.Fabric.NamedPropertyMetadata.SequenceNumber" />を持つプロパティの<see cref="P:System.Fabric.CheckSequencePropertyOperation.SequenceNumber" />引数。</span><span class="sxs-lookup"><span data-stu-id="23529-101">Compares the <see cref="P:System.Fabric.NamedPropertyMetadata.SequenceNumber" /> of a property with the <see cref="P:System.Fabric.CheckSequencePropertyOperation.SequenceNumber" /> argument.</span></span> </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="23529-102">シーケンス番号が等しくない場合、比較が失敗します。</span><span class="sxs-lookup"><span data-stu-id="23529-102">The comparison fails if the sequence numbers are not equal.</span></span> 
            <span data-ttu-id="23529-103"><see cref="T:System.Fabric.CheckSequencePropertyOperation" />バッチ内の書き込み操作のための事前条件として一般に使用します。</span><span class="sxs-lookup"><span data-stu-id="23529-103"><see cref="T:System.Fabric.CheckSequencePropertyOperation" /> is generally used as a precondition for the write operations in the batch.</span></span> <span data-ttu-id="23529-104">注意してください。 1 つ<see cref="T:System.Fabric.PropertyBatchOperation" />失敗した場合、バッチ全体が失敗し、コミットすることはできません。</span><span class="sxs-lookup"><span data-stu-id="23529-104">Note that if one <see cref="T:System.Fabric.PropertyBatchOperation" /> fails, the entire batch fails and cannot be committed.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckSequencePropertyOperation (string propertyName, long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckSequencePropertyOperation.#ctor(System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, sequenceNumber As Long)" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckSequencePropertyOperation : string * int64 -&gt; System.Fabric.CheckSequencePropertyOperation" Usage="new System.Fabric.CheckSequencePropertyOperation (propertyName, sequenceNumber)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="23529-105">A<see cref="T:System.String" />プロパティの名前を定義します。</span><span class="sxs-lookup"><span data-stu-id="23529-105">A <see cref="T:System.String" /> that defines the name of the property.</span></span></para>
        </param>
        <param name="sequenceNumber">
          <para><span data-ttu-id="23529-106">A<see cref="T:System.Int64" />に渡す操作のプロパティの予期されたシーケンス番号を定義します。</span><span class="sxs-lookup"><span data-stu-id="23529-106">A <see cref="T:System.Int64" /> that defines the expected sequence number of the property for the operation to pass.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="23529-107"><see cref="T:System.Fabric.CheckSequencePropertyOperation" /> クラスの新しいインスタンスを生成します。</span><span class="sxs-lookup"><span data-stu-id="23529-107">Instantiates a new instance of the <see cref="T:System.Fabric.CheckSequencePropertyOperation" /> class.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="23529-108">注意してください。 1 つ<see cref="T:System.Fabric.PropertyBatchOperation" />失敗した場合、バッチ全体が失敗し、コミットすることはできません。</span><span class="sxs-lookup"><span data-stu-id="23529-108">Note that if one <see cref="T:System.Fabric.PropertyBatchOperation" /> fails, the entire batch fails and cannot be committed.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CheckSequencePropertyOperation.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="System.Fabric.CheckSequencePropertyOperation.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="23529-109">予期されたシーケンス番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="23529-109">Gets the expected sequence number.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="23529-110">予期されたシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="23529-110">The expected sequence number.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>