<Type Name="BatchException" FullName="Microsoft.Azure.Batch.Common.BatchException">
  <TypeSignature Language="C#" Value="public class BatchException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.BatchException" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type BatchException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Windows Azure Batch サービスの例外を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchException (Microsoft.Azure.Batch.Common.RequestInformation requestInformation, string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Common.RequestInformation requestInformation, string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.BatchException.#ctor(Microsoft.Azure.Batch.Common.RequestInformation,System.String,System.Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Common.BatchException : Microsoft.Azure.Batch.Common.RequestInformation * string * Exception -&gt; Microsoft.Azure.Batch.Common.BatchException" Usage="new Microsoft.Azure.Batch.Common.BatchException (requestInformation, message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="requestInformation" Type="Microsoft.Azure.Batch.Common.RequestInformation" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="requestInformation">A<see cref="P:Microsoft.Azure.Batch.Common.BatchException.RequestInformation" />要求に関する詳細を含むオブジェクト。</param>
        <param name="message">例外メッセージ。</param>
        <param name="inner">内部例外。</param>
        <summary>
            指定されたパラメーターを使用して、<see cref="T:Microsoft.Azure.Batch.Common.BatchException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.RequestInformation RequestInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Common.RequestInformation RequestInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.BatchException.RequestInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestInformation As RequestInformation" />
      <MemberSignature Language="F#" Value="member this.RequestInformation : Microsoft.Azure.Batch.Common.RequestInformation" Usage="Microsoft.Azure.Batch.Common.BatchException.RequestInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.RequestInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            失敗した要求に関する情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.BatchException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="batchException.ToString " />
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
            例外を説明する文字列を生成します。
            </summary>
        <returns>例外を表す文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>