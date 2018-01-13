<Type Name="CheckExistsPropertyOperation" FullName="System.Fabric.CheckExistsPropertyOperation">
  <TypeSignature Language="C#" Value="public sealed class CheckExistsPropertyOperation : System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CheckExistsPropertyOperation extends System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.CheckExistsPropertyOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CheckExistsPropertyOperation&#xA;Inherits PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type CheckExistsPropertyOperation = class&#xA;    inherit PropertyBatchOperation" />
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
      <para>表す、<see cref="T:System.Fabric.PropertyBatchOperation" />を持つプロパティのブール型の存在と比較する、<see cref="P:System.Fabric.CheckExistsPropertyOperation.ExistenceCheck" />引数。 </para>
    </summary>
    <remarks>
      <para><see cref="T:System.Fabric.PropertyBatchOperation" />プロパティと等しくない場合、操作が失敗した、<see cref="P:System.Fabric.CheckExistsPropertyOperation.ExistenceCheck" />引数。
            <see cref="T:System.Fabric.CheckExistsPropertyOperation" />バッチ内の書き込み操作の通常の事前条件として使用されます。 注意してください。 1 つ<see cref="T:System.Fabric.PropertyBatchOperation" />失敗した場合、バッチ全体が失敗し、コミットすることはできません。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckExistsPropertyOperation (string propertyName, bool existenceCheck);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, bool existenceCheck) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckExistsPropertyOperation.#ctor(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, existenceCheck As Boolean)" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckExistsPropertyOperation : string * bool -&gt; System.Fabric.CheckExistsPropertyOperation" Usage="new System.Fabric.CheckExistsPropertyOperation (propertyName, existenceCheck)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="existenceCheck" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>プロパティの名前。</para>
        </param>
        <param name="existenceCheck">
          <para>渡す操作のプロパティが存在する必要があるかどうかを指定するフラグ。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.CheckExistsPropertyOperation" /> オブジェクトをインスタンス化します。 </para>
        </summary>
        <remarks>
          <para>存在する場合<see cref="T:System.Fabric.PropertyBatchOperation" />バッチが失敗した、全体が失敗したバッチでコミットすることはできません。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistenceCheck">
      <MemberSignature Language="C#" Value="public bool ExistenceCheck { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExistenceCheck" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CheckExistsPropertyOperation.ExistenceCheck" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExistenceCheck As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExistenceCheck : bool" Usage="System.Fabric.CheckExistsPropertyOperation.ExistenceCheck" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>渡す操作のプロパティが存在する必要があるかどうかを指定するフラグを取得します。</para>
        </summary>
        <value>
          <para>渡す操作のプロパティが存在する必要があるかどうかを指定するフラグ。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>