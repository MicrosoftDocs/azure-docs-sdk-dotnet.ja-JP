<Type Name="RedshiftUnloadSettings" FullName="Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings">
  <TypeSignature Language="C#" Value="public class RedshiftUnloadSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedshiftUnloadSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class RedshiftUnloadSettings" />
  <TypeSignature Language="F#" Value="type RedshiftUnloadSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="90ab2-101">Amazon Redshift からコピーするときに、中間の Amazon S3 に必要な Amazon S3 設定をアンロードします。</span><span class="sxs-lookup"><span data-stu-id="90ab2-101">The Amazon S3 settings needed for the interim Amazon S3 when copying from Amazon Redshift with unload.</span></span> <span data-ttu-id="90ab2-102">これにより、Amazon Redshift ソースからデータをまず S3 にアンロードし、する中間 S3 から対象となるシンクにコピーされます。</span><span class="sxs-lookup"><span data-stu-id="90ab2-102">With this, data from Amazon Redshift source will be unloaded into S3 first and then copied into the targeted sink from the interim S3.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedshiftUnloadSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="90ab2-103">RedshiftUnloadSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="90ab2-103">Initializes a new instance of the RedshiftUnloadSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedshiftUnloadSettings (Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference s3LinkedServiceName, object bucketName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference s3LinkedServiceName, object bucketName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings.#ctor(Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (s3LinkedServiceName As LinkedServiceReference, bucketName As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings" Usage="new Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings (s3LinkedServiceName, bucketName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="s3LinkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="bucketName" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="s3LinkedServiceName"><span data-ttu-id="90ab2-104">Amazon S3 の名前には、Amazon Redshift ソースからコピーするときに、アンロード操作に使用するサービスがリンクされています。</span><span class="sxs-lookup"><span data-stu-id="90ab2-104">The name of the Amazon S3 linked service which will be used for the unload operation when copying from the Amazon Redshift source.</span></span></param>
        <param name="bucketName"><span data-ttu-id="90ab2-105">Amazon Redshift ソースからアンロード データの格納に使用される中間 Amazon s3 バケット。</span><span class="sxs-lookup"><span data-stu-id="90ab2-105">The bucket of the interim Amazon S3 which will be used to store the unloaded data from Amazon Redshift source.</span></span> <span data-ttu-id="90ab2-106">バケットは、Amazon Redshift ソースと同じリージョンにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="90ab2-106">The bucket must be in the same region as the Amazon Redshift source.</span></span> <span data-ttu-id="90ab2-107">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="90ab2-107">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="90ab2-108">RedshiftUnloadSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="90ab2-108">Initializes a new instance of the RedshiftUnloadSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BucketName">
      <MemberSignature Language="C#" Value="public object BucketName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object BucketName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings.BucketName" />
      <MemberSignature Language="VB.NET" Value="Public Property BucketName As Object" />
      <MemberSignature Language="F#" Value="member this.BucketName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings.BucketName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bucketName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90ab2-109">取得またはアンロードされた Amazon Redshift ソースからデータを格納するために使用する中間の Amazon s3 バケットを設定します。</span><span class="sxs-lookup"><span data-stu-id="90ab2-109">Gets or sets the bucket of the interim Amazon S3 which will be used to store the unloaded data from Amazon Redshift source.</span></span> <span data-ttu-id="90ab2-110">バケットは、Amazon Redshift ソースと同じリージョンにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="90ab2-110">The bucket must be in the same region as the Amazon Redshift source.</span></span> <span data-ttu-id="90ab2-111">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="90ab2-111">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="S3LinkedServiceName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference S3LinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference S3LinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings.S3LinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property S3LinkedServiceName As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.S3LinkedServiceName : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings.S3LinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="s3LinkedServiceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90ab2-112">取得または Amazon Redshift ソースからコピーするときに、アンロード操作に使用されるリンク Amazon S3 サービスの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="90ab2-112">Gets or sets the name of the Amazon S3 linked service which will be used for the unload operation when copying from the Amazon Redshift source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="redshiftUnloadSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="90ab2-113">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="90ab2-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="90ab2-114">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="90ab2-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>