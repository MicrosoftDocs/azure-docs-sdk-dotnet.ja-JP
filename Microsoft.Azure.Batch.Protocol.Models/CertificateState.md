<Type Name="CertificateState" FullName="Microsoft.Azure.Batch.Protocol.Models.CertificateState">
  <TypeSignature Language="C#" Value="public enum CertificateState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed CertificateState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.CertificateState" />
  <TypeSignature Language="VB.NET" Value="Public Enum CertificateState" />
  <TypeSignature Language="F#" Value="type CertificateState = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="0d74d-101">CertificateState の値を定義します。</span><span class="sxs-lookup"><span data-stu-id="0d74d-101">Defines values for CertificateState.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateState Active = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.CertificateState.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateState.Active" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="active")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d74d-102">証明書は、プールで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="0d74d-102">The certificate is available for use in pools.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="DeleteFailed">
      <MemberSignature Language="C#" Value="DeleteFailed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateState DeleteFailed = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.CertificateState.DeleteFailed" />
      <MemberSignature Language="VB.NET" Value="DeleteFailed" />
      <MemberSignature Language="F#" Value="DeleteFailed = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateState.DeleteFailed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="deletefailed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d74d-103">ユーザーが証明書が削除されることを要求したが、証明書への参照が残っているプールがまたは 1 つまたは複数のコンピューティング ノードにまだインストールされています。</span><span class="sxs-lookup"><span data-stu-id="0d74d-103">The user requested that the certificate be deleted, but there are pools that still have references to the certificate, or it is still installed on one or more compute nodes.</span></span> <span data-ttu-id="0d74d-104">(後者発生する可能性が証明書は、プールから削除されましたが、ノードがまだ再起動されていない場合。</span><span class="sxs-lookup"><span data-stu-id="0d74d-104">(The latter can occur if the certificate has been removed from the pool, but the node has not yet restarted.</span></span> <span data-ttu-id="0d74d-105">ノードの更新の証明書は再起動時にのみ。)削除、[キャンセル] を [キャンセル] 証明書の削除操作または削除を再試行する delete 証明書の操作を使用することがあります。</span><span class="sxs-lookup"><span data-stu-id="0d74d-105">Nodes refresh their certificates only when they restart.) You may use the cancel certificate delete operation to cancel the delete, or the delete certificate operation to retry the delete.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Deleting">
      <MemberSignature Language="C#" Value="Deleting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateState Deleting = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.CertificateState.Deleting" />
      <MemberSignature Language="VB.NET" Value="Deleting" />
      <MemberSignature Language="F#" Value="Deleting = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateState.Deleting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="deleting")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d74d-106">ユーザーが証明書が削除されることを要求しましたが、削除操作がまだ完了していません。</span><span class="sxs-lookup"><span data-stu-id="0d74d-106">The user has requested that the certificate be deleted, but the delete operation has not yet completed.</span></span> <span data-ttu-id="0d74d-107">証明書の作成またはプールを更新する場合は参照できません。</span><span class="sxs-lookup"><span data-stu-id="0d74d-107">You may not reference the certificate when creating or updating pools.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>