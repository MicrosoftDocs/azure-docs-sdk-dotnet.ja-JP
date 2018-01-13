<Type Name="DataDisks" FullName="Microsoft.Azure.Management.BatchAI.Models.DataDisks">
  <TypeSignature Language="C#" Value="public class DataDisks" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataDisks extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.DataDisks" />
  <TypeSignature Language="VB.NET" Value="Public Class DataDisks" />
  <TypeSignature Language="F#" Value="type DataDisks = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ファイル サーバーの作成とデータ ディスクの設定です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDisks ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.DataDisks.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DataDisks クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDisks (int diskSizeInGB, int diskCount, string storageAccountType, Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.CachingType&gt; cachingType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 diskSizeInGB, int32 diskCount, string storageAccountType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.CachingType&gt; cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.DataDisks.#ctor(System.Int32,System.Int32,System.String,System.Nullable{Microsoft.Azure.Management.BatchAI.Models.CachingType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (diskSizeInGB As Integer, diskCount As Integer, storageAccountType As String, Optional cachingType As Nullable(Of CachingType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.DataDisks : int * int * string * Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.CachingType&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.DataDisks" Usage="new Microsoft.Azure.Management.BatchAI.Models.DataDisks (diskSizeInGB, diskCount, storageAccountType, cachingType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="diskSizeInGB" Type="System.Int32" />
        <Parameter Name="diskCount" Type="System.Int32" />
        <Parameter Name="storageAccountType" Type="System.String" />
        <Parameter Name="cachingType" Type="System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.CachingType&gt;" />
      </Parameters>
      <Docs>
        <param name="diskSizeInGB">最初のディスク サイズ (GB) の空のデータ ディスクと既存のデータ ディスクのサイズ変更の目的の新しいサイズ。</param>
        <param name="diskCount">VM にアタッチされているデータ ディスクの数。 RAID レベル 0 は、複数のディスクの場合に適用されます。</param>
        <param name="storageAccountType">ディスクで使用するストレージ アカウントの種類を指定します。 指定できる値は: Standard_LRS またはが premium_lrs の場合。</param>
        <param name="cachingType">None、ReadOnly、ReadWrite です。 既定値は None です。 パッチ可能なこのプロパティは使用されません。</param>
        <summary>
            DataDisks クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CachingType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.CachingType&gt; CachingType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.CachingType&gt; CachingType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.DataDisks.CachingType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CachingType As Nullable(Of CachingType)" />
      <MemberSignature Language="F#" Value="member this.CachingType : Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.CachingType&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.DataDisks.CachingType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cachingType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.CachingType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            None、ReadOnly、ReadWrite を取得します。 既定値は None です。 パッチ可能なこのプロパティは使用されません。
            </summary>
        <value>To be added.</value>
        <remarks>
            使用可能な値が含まれます 'none'、'readonly'、'readwrite'。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskCount">
      <MemberSignature Language="C#" Value="public int DiskCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DiskCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.DataDisks.DiskCount" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DiskCount : int with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.DataDisks.DiskCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または VM にアタッチされているデータ ディスクの数を設定します。 RAID レベル 0 は、複数のディスクの場合に適用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeInGB">
      <MemberSignature Language="C#" Value="public int DiskSizeInGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DiskSizeInGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.DataDisks.DiskSizeInGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeInGB As Integer" />
      <MemberSignature Language="F#" Value="member this.DiskSizeInGB : int with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.DataDisks.DiskSizeInGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskSizeInGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または GB の空のデータ ディスクの最初のディスク サイズと既存のデータ ディスクのサイズ変更の目的の新しいサイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public string StorageAccountType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.DataDisks.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountType As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.DataDisks.StorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、ディスクに使用するストレージ アカウントの種類を指定します。 指定できる値は: Standard_LRS またはが premium_lrs の場合。
            </summary>
        <value>To be added.</value>
        <remarks>
            使用可能な値が含まれます: 'Standard_LRS'、'Premium_LRS'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.DataDisks.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataDisks.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>