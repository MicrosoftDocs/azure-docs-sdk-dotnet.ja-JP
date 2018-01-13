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
      <para>表す、<see cref="T:System.Fabric.PropertyBatchOperation" />存在する場合に、指定したプロパティを削除します。</para>
    </summary>
    <remarks>
      <para>注意してください。 1 つ<see cref="T:System.Fabric.PropertyBatchOperation" />オブジェクトが失敗し、バッチ全体が失敗し、コミットすることはできません。</para>
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
          <para>削除するプロパティの名前。</para>
        </param>
        <summary>
          <para>作成し、インスタンス化、<see cref="T:System.Fabric.DeletePropertyOperation" />オブジェクト。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>