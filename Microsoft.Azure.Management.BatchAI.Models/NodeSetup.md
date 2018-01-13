<Type Name="NodeSetup" FullName="Microsoft.Azure.Management.BatchAI.Models.NodeSetup">
  <TypeSignature Language="C#" Value="public class NodeSetup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeSetup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.NodeSetup" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeSetup" />
  <TypeSignature Language="F#" Value="type NodeSetup = class" />
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
            VM を準備するのにには、これを使用します。 メモ: mountVolumes で指定されたボリュームのマウントされた最初およびし、setupTask を実行します。 したがって、セットアップ タスクでは、その実行にローカル mountPaths を使用できます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeSetup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.NodeSetup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            NodeSetup クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeSetup (Microsoft.Azure.Management.BatchAI.Models.SetupTask setupTask = null, Microsoft.Azure.Management.BatchAI.Models.MountVolumes mountVolumes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.BatchAI.Models.SetupTask setupTask, class Microsoft.Azure.Management.BatchAI.Models.MountVolumes mountVolumes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.NodeSetup.#ctor(Microsoft.Azure.Management.BatchAI.Models.SetupTask,Microsoft.Azure.Management.BatchAI.Models.MountVolumes)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.NodeSetup : Microsoft.Azure.Management.BatchAI.Models.SetupTask * Microsoft.Azure.Management.BatchAI.Models.MountVolumes -&gt; Microsoft.Azure.Management.BatchAI.Models.NodeSetup" Usage="new Microsoft.Azure.Management.BatchAI.Models.NodeSetup (setupTask, mountVolumes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="setupTask" Type="Microsoft.Azure.Management.BatchAI.Models.SetupTask" />
        <Parameter Name="mountVolumes" Type="Microsoft.Azure.Management.BatchAI.Models.MountVolumes" />
      </Parameters>
      <Docs>
        <param name="setupTask">クラスターのコンピューティング ノードをカスタマイズするために使用するセットアップ タスクを指定します。 NodeSetup タスクでは、VM が再起動されるたびに実行されます。 そのため、タスクのコードはべき等である必要があります。 通常、クラスター Vm 上で実行されるすべてのジョブに必要な静的データをダウンロードするか、または、ソフトウェアのダウンロードおよびインストールに使用されます。</param>
        <param name="mountVolumes">ジョブによって使用される共有ボリュームについて説明します。</param>
        <summary>
            NodeSetup クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MountVolumes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.MountVolumes MountVolumes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.MountVolumes MountVolumes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.NodeSetup.MountVolumes" />
      <MemberSignature Language="VB.NET" Value="Public Property MountVolumes As MountVolumes" />
      <MemberSignature Language="F#" Value="member this.MountVolumes : Microsoft.Azure.Management.BatchAI.Models.MountVolumes with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.NodeSetup.MountVolumes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mountVolumes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.MountVolumes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブによって使用される共有ボリューム上の情報を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetupTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.SetupTask SetupTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.SetupTask SetupTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.NodeSetup.SetupTask" />
      <MemberSignature Language="VB.NET" Value="Public Property SetupTask As SetupTask" />
      <MemberSignature Language="F#" Value="member this.SetupTask : Microsoft.Azure.Management.BatchAI.Models.SetupTask with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.NodeSetup.SetupTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="setupTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.SetupTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、クラスターのコンピューティング ノードをカスタマイズするために使用するセットアップ タスクを指定します。 NodeSetup タスクでは、VM が再起動されるたびに実行されます。 そのため、タスクのコードはべき等である必要があります。 通常、クラスター Vm 上で実行されるすべてのジョブに必要な静的データをダウンロードするか、または、ソフトウェアのダウンロードおよびインストールに使用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.NodeSetup.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="nodeSetup.Validate " />
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