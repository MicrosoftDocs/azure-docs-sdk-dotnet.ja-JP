<Type Name="DeletePropertyOperation" FullName="System.Fabric.DeletePropertyOperation">
  <TypeSignature Language="C#" Value="public sealed class DeletePropertyOperation : System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeletePropertyOperation extends System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.DeletePropertyOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeletePropertyOperation&#xA;Inherits PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type DeletePropertyOperation = class&#xA;    inherit PropertyBatchOperation" />
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
      <para><span data-ttu-id="66dff-101">表す、<see cref="T:System.Fabric.PropertyBatchOperation" />存在する場合に、指定したプロパティを削除します。</span><span class="sxs-lookup"><span data-stu-id="66dff-101">Represents a <see cref="T:System.Fabric.PropertyBatchOperation" /> that deletes a specified property if it exists.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="66dff-102">注意してください。 1 つ<see cref="T:System.Fabric.PropertyBatchOperation" />オブジェクトが失敗し、バッチ全体が失敗し、コミットすることはできません。</span><span class="sxs-lookup"><span data-stu-id="66dff-102">Note that if one <see cref="T:System.Fabric.PropertyBatchOperation" /> object fails, the entire batch fails and cannot be committed.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletePropertyOperation (string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.DeletePropertyOperation.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.DeletePropertyOperation : string -&gt; System.Fabric.DeletePropertyOperation" Usage="new System.Fabric.DeletePropertyOperation propertyName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="66dff-103">削除するプロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="66dff-103">The name of the property to be deleted.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="66dff-104">作成し、インスタンス化、<see cref="T:System.Fabric.DeletePropertyOperation" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="66dff-104">Creates and instantiates a <see cref="T:System.Fabric.DeletePropertyOperation" /> object.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>