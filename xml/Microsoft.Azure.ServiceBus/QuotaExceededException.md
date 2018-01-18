<Type Name="QuotaExceededException" FullName="Microsoft.Azure.ServiceBus.QuotaExceededException">
  <TypeSignature Language="C#" Value="public sealed class QuotaExceededException : Microsoft.Azure.ServiceBus.ServiceBusException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit QuotaExceededException extends Microsoft.Azure.ServiceBus.ServiceBusException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.QuotaExceededException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class QuotaExceededException&#xA;Inherits ServiceBusException" />
  <TypeSignature Language="F#" Value="type QuotaExceededException = class&#xA;    inherit ServiceBusException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.ServiceBusException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0db9c-101">エンティティに割り当てられたクォータ (エンティティの最大サイズまたはその他の接続など) を超えた場合にスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="0db9c-101">The exception that is thrown when the Quota (Entity Max Size or other Connection etc) allocated to the Entity has exceeded.</span></span>  <span data-ttu-id="0db9c-102">呼び出し元は、クォータの超過、適切な操作を表示するエラー メッセージを確認する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0db9c-102">Callers should check the error message to see which of the Quota exceeded and take appropriate action.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QuotaExceededException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QuotaExceededException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.QuotaExceededException : string -&gt; Microsoft.Azure.ServiceBus.QuotaExceededException" Usage="new Microsoft.Azure.ServiceBus.QuotaExceededException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QuotaExceededException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QuotaExceededException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.QuotaExceededException : string * Exception -&gt; Microsoft.Azure.ServiceBus.QuotaExceededException" Usage="new Microsoft.Azure.ServiceBus.QuotaExceededException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <param name="innerException">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>