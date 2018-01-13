<Type Name="PoolInformation" FullName="Microsoft.Azure.Batch.PoolInformation">
  <TypeSignature Language="C#" Value="public class PoolInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.PoolInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolInformation" />
  <TypeSignature Language="F#" Value="type PoolInformation = class&#xA;    interface ITransportObjectProvider&lt;PoolInformation&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ジョブのプールに割り当て方法を指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.PoolInformation" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoPoolSpecification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AutoPoolSpecification AutoPoolSpecification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.AutoPoolSpecification AutoPoolSpecification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolInformation.AutoPoolSpecification" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoPoolSpecification As AutoPoolSpecification" />
      <MemberSignature Language="F#" Value="member this.AutoPoolSpecification : Microsoft.Azure.Batch.AutoPoolSpecification with get, set" Usage="Microsoft.Azure.Batch.PoolInformation.AutoPoolSpecification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AutoPoolSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または作成される自動プールのプロパティを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティが設定されている場合、し<see cref="P:Microsoft.Azure.Batch.PoolInformation.PoolId" />残す必要のある設定を解除します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolId">
      <MemberSignature Language="C#" Value="public string PoolId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolInformation.PoolId" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolId As String" />
      <MemberSignature Language="F#" Value="member this.PoolId : string with get, set" Usage="Microsoft.Azure.Batch.PoolInformation.PoolId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクの実行に使用できる既存のプールの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティが設定されている場合、し<see cref="P:Microsoft.Azure.Batch.PoolInformation.AutoPoolSpecification" />残す必要のある設定を解除します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>