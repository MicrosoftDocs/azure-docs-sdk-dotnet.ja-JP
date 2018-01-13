<Type Name="AutoScaleRun" FullName="Microsoft.Azure.Batch.AutoScaleRun">
  <TypeSignature Language="C#" Value="public class AutoScaleRun" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoScaleRun extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.AutoScaleRun" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoScaleRun" />
  <TypeSignature Language="F#" Value="type AutoScaleRun = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            結果と評価またはプールの自動スケール式の実行からのエラーです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AutoScaleRunError Error { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.AutoScaleRunError Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoScaleRun.Error" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Error As AutoScaleRunError" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Batch.AutoScaleRunError" Usage="Microsoft.Azure.Batch.AutoScaleRun.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AutoScaleRunError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            評価が成功した場合、エラーが発生しました、プールで自動スケール式の評価の詳細を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public string Results { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoScaleRun.Results" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Results As String" />
      <MemberSignature Language="F#" Value="member this.Results : string" Usage="Microsoft.Azure.Batch.AutoScaleRun.Results" />
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
            自動スケール式の評価に使用されるすべての変数の最終的な値を取得します。 フォーム $variable に各変数の値が返されます = 値、および変数はセミコロンで区切って指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTime Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoScaleRun.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Timestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTime" Usage="Microsoft.Azure.Batch.AutoScaleRun.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            自動スケール式が最後に評価された時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>