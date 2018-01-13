<Type Name="SharedAccessBlobHeaders" FullName="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders">
  <TypeSignature Language="C#" Value="public sealed class SharedAccessBlobHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedAccessBlobHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedAccessBlobHeaders" />
  <TypeSignature Language="F#" Value="type SharedAccessBlobHeaders = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            SAS を使用してアクセスされた blob と共に返される省略可能なヘッダーを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessBlobHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessBlobHeaders (Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders sharedAccessBlobHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders sharedAccessBlobHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders.#ctor(Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders -&gt; Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders" Usage="new Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders sharedAccessBlobHeaders" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sharedAccessBlobHeaders" Type="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders" />
      </Parameters>
      <Docs>
        <param name="sharedAccessBlobHeaders">一連の<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders" />を複製します。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders" />クラスは、既存のインスタンスに基づいています。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CacheControl">
      <MemberSignature Language="C#" Value="public string CacheControl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CacheControl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders.CacheControl" />
      <MemberSignature Language="VB.NET" Value="Public Property CacheControl As String" />
      <MemberSignature Language="F#" Value="member this.CacheControl : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders.CacheControl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または blob と共に返される cache-control ヘッダーを設定します。
            </summary>
        <value>Cache-control 値を含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentDisposition">
      <MemberSignature Language="C#" Value="public string ContentDisposition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentDisposition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders.ContentDisposition" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentDisposition As String" />
      <MemberSignature Language="F#" Value="member this.ContentDisposition : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders.ContentDisposition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または blob と共に返される content-disposition ヘッダーを設定します。
            </summary>
        <value>Content-disposition 値を含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentEncoding">
      <MemberSignature Language="C#" Value="public string ContentEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders.ContentEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentEncoding As String" />
      <MemberSignature Language="F#" Value="member this.ContentEncoding : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders.ContentEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または blob と共に返される content-encoding ヘッダーを設定します。
            </summary>
        <value>Content-encoding 値を含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLanguage">
      <MemberSignature Language="C#" Value="public string ContentLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders.ContentLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentLanguage As String" />
      <MemberSignature Language="F#" Value="member this.ContentLanguage : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders.ContentLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または blob と共に返される content-language ヘッダーを設定します。
            </summary>
        <value>Content-language 値を含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または blob と共に返される content-type ヘッダーを設定します。
            </summary>
        <value>コンテンツの種類の値を含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>