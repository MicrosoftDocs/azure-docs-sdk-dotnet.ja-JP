<Type Name="CertificateVisibility" FullName="Microsoft.Azure.Batch.Common.CertificateVisibility">
  <TypeSignature Language="C#" Value="public enum CertificateVisibility" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed CertificateVisibility extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.CertificateVisibility" />
  <TypeSignature Language="VB.NET" Value="Public Enum CertificateVisibility" />
  <TypeSignature Language="F#" Value="type CertificateVisibility = " />
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
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="7c8a3-101">証明書のプライベート データにアクセス権をコンピューティング ノード上でユーザー アカウントを指定します。</span><span class="sxs-lookup"><span data-stu-id="7c8a3-101">Specifies which user accounts on a compute node should have access to the private data of a certificate.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.CertificateVisibility None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.CertificateVisibility.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.Azure.Batch.Common.CertificateVisibility.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.CertificateVisibility</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c8a3-102">証明書には、可視性がありません。</span><span class="sxs-lookup"><span data-stu-id="7c8a3-102">The certificate has no visibility.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RemoteUser">
      <MemberSignature Language="C#" Value="RemoteUser" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.CertificateVisibility RemoteUser = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.CertificateVisibility.RemoteUser" />
      <MemberSignature Language="VB.NET" Value="RemoteUser" />
      <MemberSignature Language="F#" Value="RemoteUser = 4" Usage="Microsoft.Azure.Batch.Common.CertificateVisibility.RemoteUser" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.CertificateVisibility</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c8a3-103">リモートでアクセス (リモート デスクトップを使用して) ノードのアカウント。</span><span class="sxs-lookup"><span data-stu-id="7c8a3-103">The accounts under which users remotely access the node (using Remote Desktop).</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="StartTask" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.CertificateVisibility StartTask = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.CertificateVisibility.StartTask" />
      <MemberSignature Language="VB.NET" Value="StartTask" />
      <MemberSignature Language="F#" Value="StartTask = 1" Usage="Microsoft.Azure.Batch.Common.CertificateVisibility.StartTask" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.CertificateVisibility</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c8a3-104">開始タスクを実行するユーザー アカウント。</span><span class="sxs-lookup"><span data-stu-id="7c8a3-104">The user account under which the start task is run.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Task">
      <MemberSignature Language="C#" Value="Task" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.CertificateVisibility Task = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.CertificateVisibility.Task" />
      <MemberSignature Language="VB.NET" Value="Task" />
      <MemberSignature Language="F#" Value="Task = 2" Usage="Microsoft.Azure.Batch.Common.CertificateVisibility.Task" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.CertificateVisibility</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c8a3-105">どのジョブのタスクを実行するアカウント。</span><span class="sxs-lookup"><span data-stu-id="7c8a3-105">The accounts under which job tasks are run.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>