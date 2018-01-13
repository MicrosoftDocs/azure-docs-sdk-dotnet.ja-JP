<Type Name="FileProperties" FullName="Microsoft.Azure.Batch.FileProperties">
  <TypeSignature Language="C#" Value="public class FileProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.FileProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class FileProperties" />
  <TypeSignature Language="F#" Value="type FileProperties = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            コンピューティング ノード上のファイルのプロパティです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContentLength">
      <MemberSignature Language="C#" Value="public long ContentLength { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ContentLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileProperties.ContentLength" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContentLength As Long" />
      <MemberSignature Language="F#" Value="member this.ContentLength : int64" Usage="Microsoft.Azure.Batch.FileProperties.ContentLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファイルの長さを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileProperties.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string" Usage="Microsoft.Azure.Batch.FileProperties.ContentType" />
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
            ファイルのコンテンツの種類を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileProperties.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.FileProperties.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファイル作成時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileMode">
      <MemberSignature Language="C#" Value="public string FileMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileProperties.FileMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FileMode As String" />
      <MemberSignature Language="F#" Value="member this.FileMode : string" Usage="Microsoft.Azure.Batch.FileProperties.FileMode" />
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
            ファイルのアクセス許可属性を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティは、Linux ノードに対してのみ返されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public DateTime LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileProperties.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastModified : DateTime" Usage="Microsoft.Azure.Batch.FileProperties.LastModified" />
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
            ファイルが最後に変更された日時を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>