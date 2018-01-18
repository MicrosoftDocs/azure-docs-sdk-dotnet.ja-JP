<Type Name="AutoScaleRunError" FullName="Microsoft.Azure.Batch.AutoScaleRunError">
  <TypeSignature Language="C#" Value="public class AutoScaleRunError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoScaleRunError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.AutoScaleRunError" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoScaleRunError" />
  <TypeSignature Language="F#" Value="type AutoScaleRunError = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="09c35-101">実行するか、プールの自動スケール式を評価するときに発生したエラーです。</span><span class="sxs-lookup"><span data-stu-id="09c35-101">An error that occurred when executing or evaluating a pool autoscale formula.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoScaleRunError.Code" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string" Usage="Microsoft.Azure.Batch.AutoScaleRunError.Code" />
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
            <span data-ttu-id="09c35-102">自動スケール エラーのコードを取得します。</span><span class="sxs-lookup"><span data-stu-id="09c35-102">Gets a code for the autoscale error.</span></span> <span data-ttu-id="09c35-103">参照してください<see cref="T:Microsoft.Azure.Batch.Common.BatchErrorCodeStrings" />使用可能な値です。</span><span class="sxs-lookup"><span data-stu-id="09c35-103">See <see cref="T:Microsoft.Azure.Batch.Common.BatchErrorCodeStrings" /> for possible values.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoScaleRunError.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Batch.AutoScaleRunError.Message" />
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
            <span data-ttu-id="09c35-104">ユーザー インターフェイスでの表示に適したするもので、自動スケール エラーを説明するメッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="09c35-104">Gets a message describing the autoscale error, intended to be suitable for display in a user interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NameValuePair&gt; Values { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.NameValuePair&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoScaleRunError.Values" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Values As IReadOnlyList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NameValuePair&gt;" Usage="Microsoft.Azure.Batch.AutoScaleRunError.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09c35-105">自動スケール エラーに関連する追加のエラー詳細の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="09c35-105">Gets a list of additional error details related to the autoscale error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>