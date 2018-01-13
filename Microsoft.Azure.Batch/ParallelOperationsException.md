<Type Name="ParallelOperationsException" FullName="Microsoft.Azure.Batch.ParallelOperationsException">
  <TypeSignature Language="C#" Value="public class ParallelOperationsException : AggregateException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ParallelOperationsException extends System.AggregateException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ParallelOperationsException" />
  <TypeSignature Language="VB.NET" Value="Public Class ParallelOperationsException&#xA;Inherits AggregateException" />
  <TypeSignature Language="F#" Value="type ParallelOperationsException = class&#xA;    inherit AggregateException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.AggregateException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            例外発生時に 1 つまたは多くの操作で、並列の一連の操作は失敗します。  
            <see cref="P:System.AggregateException.InnerExceptions" />コレクションには、失敗した操作の各例外が含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ParallelOperationsException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="parallelOperationsException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在の <see cref="T:Microsoft.Azure.Batch.ParallelOperationsException" /> の文字列表現を作成して返します。
            </summary>
        <returns>現在の例外の文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>