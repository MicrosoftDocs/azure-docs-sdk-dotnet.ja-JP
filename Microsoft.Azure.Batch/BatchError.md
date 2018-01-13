<Type Name="BatchError" FullName="Microsoft.Azure.Batch.BatchError">
  <TypeSignature Language="C#" Value="public class BatchError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.BatchError" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchError" />
  <TypeSignature Language="F#" Value="type BatchError = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="5ff02-101">Azure Batch のサービスから受信したエラー。</span><span class="sxs-lookup"><span data-stu-id="5ff02-101">An error received from the Azure Batch service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchError.Code" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string" Usage="Microsoft.Azure.Batch.BatchError.Code" />
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
            <span data-ttu-id="5ff02-102">エラーのコードを取得します。</span><span class="sxs-lookup"><span data-stu-id="5ff02-102">Gets a code for the error.</span></span> <span data-ttu-id="5ff02-103">参照してください<see cref="T:Microsoft.Azure.Batch.Common.BatchErrorCodeStrings" />使用可能な値です。</span><span class="sxs-lookup"><span data-stu-id="5ff02-103">See <see cref="T:Microsoft.Azure.Batch.Common.BatchErrorCodeStrings" /> for possible values.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ErrorMessage Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ErrorMessage Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchError.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As ErrorMessage" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.Azure.Batch.ErrorMessage" Usage="Microsoft.Azure.Batch.BatchError.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ErrorMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ff02-104">ユーザー インターフェイスでの表示に適したするもので、エラーを説明するメッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="5ff02-104">Gets a message describing the error, intended to be suitable for display in a user interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.BatchErrorDetail&gt; Values { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.BatchErrorDetail&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchError.Values" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Values As IReadOnlyList(Of BatchErrorDetail)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.BatchErrorDetail&gt;" Usage="Microsoft.Azure.Batch.BatchError.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.BatchErrorDetail&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ff02-105">エラーに関する追加情報を含むキーと値のペアのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="5ff02-105">Gets a collection of key-value pairs containing additional details about the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>