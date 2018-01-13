<Type Name="ResizeError" FullName="Microsoft.Azure.Batch.ResizeError">
  <TypeSignature Language="C#" Value="public class ResizeError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResizeError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ResizeError" />
  <TypeSignature Language="VB.NET" Value="Public Class ResizeError" />
  <TypeSignature Language="F#" Value="type ResizeError = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            プールのサイズを変更するときに発生したエラーです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResizeError.Code" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string" Usage="Microsoft.Azure.Batch.ResizeError.Code" />
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
            エラーのサイズを変更、プール用のコードを取得します。 参照してください<see cref="T:Microsoft.Azure.Batch.Common.PoolResizeErrorCodes" />使用可能な値です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResizeError.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Batch.ResizeError.Message" />
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
            ユーザー インターフェイスでの表示に適したするもので、プール サイズ変更エラーを説明するメッセージを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NameValuePair&gt; Values { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.NameValuePair&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResizeError.Values" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Values As IReadOnlyList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NameValuePair&gt;" Usage="Microsoft.Azure.Batch.ResizeError.Values" />
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
            サイズ変更エラーをプールに関連する追加のエラー詳細の一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>